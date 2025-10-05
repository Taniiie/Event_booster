# 🎤 Event & Webinar Engagement Booster

A comprehensive Streamlit application designed to boost event and webinar engagement through personalized communications, analytics, and automated follow-ups.

## ✨ Features

- **📊 Interactive Dashboard**: Real-time event statistics and attendance analytics
- **📧 Pre-Event Reminders**: Personalized reminder templates based on attendee interests
- **🙏 Post-Event Follow-ups**: Automated thank you messages and re-engagement campaigns
- **💡 Insights & Analytics**: Deep dive into attendee interests and event performance
- **🔍 Search & Filter**: Advanced search functionality for attendee management
- **📥 Export Capabilities**: Download reminders, follow-ups, and filtered data

## 🚀 Quick Start

### 1. Setup Environment

```bash
# Create project folder
mkdir event_booster && cd event_booster

# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows:
venv\Scripts\activate
# Linux/Mac:
source venv/bin/activate
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Application

```bash
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`

## 📁 Project Structure

```
event_booster/
├── app.py              # Main Streamlit application
├── attendees.csv       # Sample attendee data
├── requirements.txt    # Python dependencies
└── README.md          # This file
```

## 📊 Sample Data Format

The `attendees.csv` file should have the following columns:

| Column | Description | Example |
|--------|-------------|---------|
| Name | Attendee name | "Nilesh" |
| Email | Email address | "nilesh@email.com" |
| Interests | Semicolon-separated interests | "AI;SaaS" |
| Registered_Event | Event name | "AI for Startups" |
| Attended | Attendance status | "Yes" or "No" |

## 🎯 Key Sections

### Dashboard
- **Key Metrics**: Total registered, attended, attendance rate, total events
- **Event Summary**: Registration and attendance breakdown by event
- **Visual Analytics**: Interactive charts and graphs

### Pre-Event Reminders
- **Standard Reminders**: Generic event reminders
- **Personalized Reminders**: Interest-based customized messages
- **Last Chance Reminders**: Urgent pre-event notifications
- **Export Feature**: Download individual reminder templates

### Post-Event Follow-ups
- **Attendee Thank You**: Appreciation messages with resources
- **No-show Re-engagement**: Special offers for missed attendees
- **Bulk Operations**: Download all follow-up messages

### Insights & Analytics
- **Interest Analysis**: Popular categories and distribution
- **Event Performance**: Attendance rates and recommendations
- **Visual Reports**: Interactive charts and performance metrics

### Search & Filter
- **Name Search**: Find attendees by name
- **Event Filter**: Filter by specific events
- **Attendance Filter**: Filter by attendance status
- **Export Results**: Download filtered attendee lists

## 🛠️ Customization

### Adding New Events
1. Update the `attendees.csv` file with new event data
2. The app will automatically detect and display new events

### Modifying Templates
- Edit the reminder and follow-up message templates in `app.py`
- Customize the styling by modifying the CSS in the application

### Adding New Features
- The modular design makes it easy to add new sections
- Follow the existing pattern for navigation and layout

## 📈 Analytics Features

- **Real-time Metrics**: Live updates of attendance statistics
- **Interest Tracking**: Monitor popular topics and trends
- **Event Performance**: Compare attendance rates across events
- **Engagement Insights**: Identify high-performing content areas

## 🎨 UI/UX Features

- **Responsive Design**: Works on desktop and mobile devices
- **Interactive Charts**: Powered by Plotly for rich visualizations
- **Modern Styling**: Clean, professional interface with custom CSS
- **Intuitive Navigation**: Easy-to-use sidebar navigation
- **Export Capabilities**: Download data and templates as needed

## 🔧 Technical Requirements

- Python 3.7+
- Streamlit 1.28+
- Pandas for data manipulation
- Plotly for interactive visualizations
- Matplotlib/Seaborn for additional charts

## 📝 Usage Tips

1. **Data Preparation**: Ensure your CSV file follows the required format
2. **Regular Updates**: Update attendee data regularly for accurate analytics
3. **Template Customization**: Modify message templates to match your brand voice
4. **Export Features**: Use download buttons to save communications for records
5. **Performance Monitoring**: Use the analytics section to track engagement trends

## 🚀 Future Enhancements

- Email integration for direct sending
- Calendar integration for event scheduling
- Advanced segmentation based on multiple criteria
- A/B testing for message templates
- Integration with popular event platforms
- Mobile app version

## 📞 Support

For questions or issues, please refer to the Streamlit documentation or create an issue in the project repository.

---

**Built with ❤️ using Streamlit**

*Boost your event engagement with personalized communications!*
