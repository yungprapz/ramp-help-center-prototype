# Ramp Help Center Interactive Prototype

An interactive HTML prototype for the Ramp Help Center featuring:

- Modern responsive design
- Interactive search functionality  
- Category-based help articles
- Contact support features
- FAQ sections
- User-friendly navigation

## Features

### Interactive Authentication Toggle
- Switch between authenticated and guest user experiences
- Personalized content delivery based on user authentication status
- Role-based content filtering and recommendations

### AI-Powered Content Retrieval
- Detailed explanation of the AI system architecture
- Contextual understanding based on user role, tier, geography, and account settings
- Semantic search with natural language processing
- Personalized ranking based on usage patterns and preferences
- Continuous learning through user feedback and engagement metrics

### CMS Features
- Article creation with rich text editor
- Workflow management (Draft → Under Review → Published)
- Version control and annotations system
- Analytics dashboard with engagement metrics
- Content metadata structure for personalization

### User Experience Features
- **Authenticated Users**: Personalized dashboard with user context, quick answers, and recommended articles
- **Guest Users**: Role selection interface with tailored content for Cardholders, Accountants, and Admins
- Responsive layout for all devices
- Interactive search with real-time filtering
- Categorized help content organized by user roles
- Clean, professional UI design with modern gradients and animations

### Technical Specifications
- Pure HTML, CSS, and JavaScript implementation
- No external dependencies
- Mobile-responsive design with CSS Grid and Flexbox
- Interactive components with smooth animations
- Accessible design following modern web standards

## Architecture

### AI Content Retrieval Process
1. **Context Analysis** - Analyzes user authentication status, role, tier, geography, and session context
2. **Query Processing** - Natural language processing to interpret user questions and extract intent
3. **Content Matching** - Semantic search using vector embeddings to match content
4. **Personalized Ranking** - Results ranked by relevance, user context, and historical patterns
5. **Continuous Learning** - Machine learning improvements based on user feedback

### Sample Article Metadata Structure
```json
{
  "article_id": "art_001",
  "title": "Managing User Permissions in Enterprise Accounts",
  "metadata": {
    "role": ["admin", "finance_manager"],
    "tier": ["enterprise", "growth"],
    "geography": ["US", "CA", "UK"],
    "category": "user_management",
    "difficulty": "intermediate",
    "estimated_read_time": "5 minutes",
    "helpfulness_score": 0.89,
    "engagement_metrics": {
      "views": 1247,
      "helpful_votes": 1109,
      "completion_rate": 0.78
    }
  }
}
```

## Deployment

This prototype is deployed using GitHub Pages and accessible at the provided URL.

## Usage

Open index.html in a web browser or access the GitHub Pages URL to view the interactive prototype.

### Interactive Features
- **Authentication Toggle**: Switch between authenticated and guest user views
- **Role Selection**: Choose user role (Cardholder, Accountant, Admin) for personalized content
- **Article Filtering**: Filter content by category (Admin, Enterprise, Cards, Billing)
- **Quick Answers**: Expandable Q&A sections with interactive toggles
- **CMS Tabs**: Navigate between Create Article, Workflow, Version Control, and Analytics
- **Article Viewer**: Click on articles to view detailed content in overlay

## Future Development Notes
- Implement vector database for semantic search
- Add A/B testing framework for ranking algorithms
- Integration with user analytics platform
- Real-time feedback processing system
- Chart.js integration for analytics visualizations
- Backend API integration for dynamic content management

## Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive design
- Progressive enhancement for older browsers

---

*This prototype demonstrates the comprehensive features and user experience design for the Ramp Help Center, showcasing both the customer-facing interface and the underlying AI-powered content management system.*