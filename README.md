# UBCBC
## Link to the site 👉 https://ubc-bc.site
#### Test User Login:
#### - Username: Test@email.com
#### - Password: 
## Check out how it works here 👉 https://youtu.be/yqe2H05G6Ho 

## Inspiration 💡  
Inspired by the discontinuation of our university’s event management system (AMS Campus Base) and frustrations with alternatives like Eventbrite/Bounce, we built UBCBC. Existing tools lacked automatic scheduling, customizable event management, and tracking for member signups. We created an all-in-one platform for UBC's badminton club to automate event workflows, track members, reduce exec workload, and replace fragmented tools with a unified solution.  

---

## What it does 🔍  
Empowers club executives to:  
✅ **Automatically create events** every Monday via cron.  
✅ **Manage waitlists** using PostgreSQL triggers for real-time signup updates.  
✅ **Verify users** via OTP email & password recovery (Brevo SMTP integration).  
✅ **Control access** with JWT-based sessions and role-based admin features (React Context).  
✅ **Secure data** with Argon2 password hashing and SQL-injection prevention.  
✅ **Track members** via attendance logs, skill tags, and no-show analytics.  
✅ **Mobile-first design** for on-the-go event check-ins and management.  

---

## How we built it 🦾  
**Tech Stack**: React (Frontend), Node.js/Express (Backend), PostgreSQL (DB), Figma (Design).  
**Workflow**:  
1. **Design & Planning**:  
   - Prototyped UI/UX in Figma with feedback from non-technical club execs.  
   - Adopted **Agile sprints** to ship features weekly.  
2. **Development**:  
   - **Frontend**: React with Context API for JWT session/role management.  
   - **Backend**: RESTful Express.js routes; Brevo integration for emails.  
   - **Database**: PostgreSQL with triggers for waitlist automation.  
3. **Security**:  
   - Argon2 for password hashing; parameterized queries to block SQL injections.  
4. **Deployment**:  
   - Hosted on Render/Netlify;  

---

## Challenges we ran into 🧠  
1. **Email Service Integration**: Brevo’s SMTP configuration required debugging edge cases (e.g., OTP timeouts).  
2. **Real-Time Waitlists**: Ensuring PostgreSQL triggers efficiently handled concurrent signups without conflicts.  
3. **JWT Session Sync**: Managing token expiration and role-based UI updates across React components.  
4. **Legacy System Gaps**: Replicating discontinued features (e.g., automated scheduling) from scratch.  
5. **Stakeholder Alignment**: Balancing non-technical exec requests with technical constraints during sprints.  

---

## Accomplishments we’re proud of 🌟 
- ⚡️ **Solving a Genuine Problem** We didn’t just build a project – we killed a daily frustration. For club executives drowning in broken tools, UBCBC saved them 15+ hours/month and became the club's operational backbone.
- 🚀 **Automated event engine** saving 10+ hours/month for club execs.  
- 🔒 **Security** via Argon2, JWT, and input sanitization.  
- 📱 **Mobile-first UI** praised by 50+ student users during testing.  
- ✉️ **Seamless Email verification and Password Recovery** OTP email deliverability for verification/recovery.  
- ⚙️ **PostgreSQL triggers** handling 500+ concurrent waitlist signups.  
- 🤝 **Agile collaboration** with non-technical stakeholders to prioritize impactful features.  

---

## What we learned ✍️  
1. **Trade-Offs > Perfection**: Shipping a functional MVP fast (e.g., cron-based automation) trumped over-engineering.  
2. **Security is Iterative**: Layered defenses (hashing + sanitization + JWT) are non-negotiable.  
3. **Stakeholder Empathy**: Involving non-tech users early uncovered critical UX pain points (e.g., mobile check-ins).  
4. **Database Magic**: PostgreSQL triggers can replace complex backend logic for real-time workflows.  
5. **Agile Flexibility**: Weekly sprints forced ruthless prioritization but accelerated user-centric results.  

---  
## Links to The Creators 👨‍💻
### Dominic Huang:
- Portfolio: https://dom4489.github.io/Dominic-Huang/
- GitHub: https://github.com/Dom4489
- LinkedIn: https://www.linkedin.com/in/dominic-huang1972/
### Rioto Oka:
- Portfolio: https://www.rioto-oka.com/
- GitHub: https://github.com/okarioto
- LinkedIn: https://www.linkedin.com/in/okarioto/
