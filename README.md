\# 🌱 Grow Mutual Fund Voice Agent



AI-Powered Advisor Appointment Scheduler with MCP Integration



\## 🎯 Overview



A sophisticated voice agent system for booking advisor appointments at Grow Mutual Fund through natural conversation.



\## ✨ Features



\- 5 supported intents (book, reschedule, cancel, prepare, check availability)

\- Natural conversation flow with compliance disclaimers

\- MCP integration (Calendar, Notes, Email)

\- Booking code generation (NL-AXXXX format)

\- No PII collection during call

\- IST timezone specification

\- Waitlist management



\## 🚀 Demo



\*\*Live Demo:\*\* \[Open index.html in browser]



\*\*Repository:\*\* https://github.com/YOUR-USERNAME/grow-voice-agent



\## 📸 Screenshots



\### Calendar Hold

\- \*\*Title:\*\* Advisor Q\&A — SIP/Mandates — NL-A7342

\- \*\*Date:\*\* 2024-12-23 (Monday)

\- \*\*Time:\*\* 10:00 IST

\- \*\*Duration:\*\* 30 minutes

\- \*\*Status:\*\* Tentative



\### Notes Entry

\*\*Document:\*\* Advisor Pre-Bookings

```

2024-12-22T14:23:45.789Z | SIP/Mandates | 2024-12-23 10:00 IST | NL-A7342 | Status: Pending Contact Details

```



\### Email Draft

\*\*To:\*\* advisors@grow.mfund.in  

\*\*Subject:\*\* New Appointment Request - NL-A7342 - SIP/Mandates  

\*\*Status:\*\* ⏳ Pending Approval



\## 🎙️ Supported Intents



1\. \*\*Book New Appointment\*\* - Complete booking flow

2\. \*\*Reschedule\*\* - Modify existing booking

3\. \*\*Cancel\*\* - Cancel appointment

4\. \*\*What to Prepare\*\* - Pre-meeting checklist

5\. \*\*Check Availability\*\* - View open slots



\## 📋 Conversation Flow

```

Greeting → Disclaimer → Topic Selection → Time Preference → 

Slot Offer → Confirmation → Booking Code → Secure Link

```



\## 🔧 MCP Integration



\- \*\*Calendar Hold:\*\* Creates tentative 30-min appointment

\- \*\*Notes Entry:\*\* Appends to "Advisor Pre-Bookings" document  

\- \*\*Email Draft:\*\* Prepares advisor notification (approval-gated)



\## 🛠️ Tech Stack



\- React 18+

\- Tailwind CSS

\- Lucide React Icons

\- MCP Protocol Integration



\## 📝 Topics Available



\- KYC/Onboarding

\- SIP/Mandates

\- Statements/Tax Docs

\- Withdrawals \& Timelines

\- Account Changes/Nominee



\## 🔒 Compliance \& Safety



\- ✅ Investment advice disclaimer

\- ✅ No PII collected during call

\- ✅ Time confirmation in IST with day names

\- ✅ Human approval required for emails

\- ✅ Secure completion portal

\- ✅ Waitlist option when no slots available



\## 📞 Usage



1\. Click "Start Call"

2\. Select intent (e.g., "book new")

3\. Choose advisory topic

4\. Provide time preference

5\. Select from 2 offered slots

6\. Confirm booking details

7\. Receive booking code (NL-AXXXX)

8\. Visit secure link to complete



\## 🗓️ Mock Calendar



Available slots:

\- Dec 23 (Monday): 10:00, 14:00, 15:00 IST

\- Dec 24 (Tuesday): 10:00, 11:00, 15:00 IST

\- Dec 26 (Thursday): 10:00, 11:00, 14:00 IST



\## 🔄 Reschedule \& Cancel



Both flows require booking code validation (NL-AXXXX format). System retrieves existing booking, offers new slots or confirms cancellation with MCP actions.



\## 📄 License



MIT License



\## 👤 Author



Voice Agent Project for Grow Mutual Fund



\## 🙏 Acknowledgments



Built with Claude AI and MCP Protocol

