HabitHero - Gamified Productivity Platform

HabitHero transforms productivity into an immersive, RPG-style experience. Track habits, complete tasks, and level up your character through interactive challenges and rewards, with dynamic character animations and game-inspired mechanics based on the popular anime Solo-Leveling

🎮 Features
Character Development System
Custom Character Avatar: Visual representation that evolves as you progress
Advanced Animation System: Multiple pose states including idle, celebration, and level-up sequences
Cloud-inspired Design: Character sprite features Cloud's iconic spiky blonde hair, SOLDIER uniform with shoulder pauldrons, and signature details
XP and Leveling
XP-Based Progression: Earn experience points for completing tasks and building streaks
Level-Up Celebrations: Visual effects and animations when reaching new levels
Reward Unlocks: New items and customizations become available as you level up
Productivity Tools
Pomodoro Timer: Focus in timed intervals with dynamic XP rewards (5 XP per 25-minute session)
Habit Tracking: Create and track habits with customizable frequency and XP rewards
Quest System: Organize tasks using the Eisenhower Matrix for priority management
XP Rewards: Tasks award different XP based on priority (urgent+important: 50 XP, important: 30 XP, urgent: 20 XP, standard: 10 XP)
Social Features
Leaderboard System: Compare progress with others
Player Rankings: Visual ranking with customizable badges for top performers
Profile Customization: Create your public profile with avatar and color scheme
Engagement Systems
Streak Tracking: Daily login streak with internal clock tracking for accuracy
Weekly Streak Bonuses: Earn 100 XP per week of consistent daily logins
Visual Flame Indicators: Dynamic flame visualization for streak progress
Celebration System: Solo Leveling inspired confetti effects and status windows
Visual Design
Solo Leveling Aesthetic: Dark color scheme with sharp angular elements and thin glowing borders
Distinctive UI Components: Status windows similar to the manhwa/anime style
Custom Scrollbars: Themed scrollbars in desktop mode matching the aesthetic
Responsive Design: Optimized for mobile and desktop experiences
🚀 Technology Stack
Frontend: React with TypeScript
State Management: React Context API
Styling: Tailwind CSS with ShadCN UI components
Animation: CSS animations and React Spring
Data Persistence: Local Storage with cloud sync capability
API Integration: Supabase for optional cloud synchronization
Build Tools: Vite for fast development and bundling
🔧 Installation & Setup
Clone the repository
git clone https://github.com/yourusername/levelup.git
cd levelup
Install dependencies
npm install
Start the development server
npm run dev
Open your browser and navigate to http://localhost:5000
🔑 Optional: Cloud Synchronization
The app works fully in local-only mode, but you can enable cloud synchronization by providing Supabase credentials:

Create a Supabase account and project at supabase.com
Add the following environment variables:
SUPABASE_URL
SUPABASE_ANON_KEY
VITE_SUPABASE_URL
VITE_SUPABASE_ANON_KEY
💡 Usage Tips
Pomodoro Technique: Use the 25-minute work sessions followed by 5-minute breaks for optimal productivity
Eisenhower Matrix: Prioritize tasks by importance and urgency in the Quests section
Streak Maintenance: Log in daily to maintain your streak and earn bonus XP rewards
Habit Building: Start with a few key habits before adding more to your routine
📱 Mobile-First Design
LevelUp is designed to work seamlessly on both desktop and mobile devices, with a responsive interface that adapts to your screen size.

🛠️ Development
Structure
/client: Frontend React application
/server: Express backend for API handling
/shared: Shared types and utilities
/attached_assets: Static assets and images
Key Components
AppContext.tsx: Central state management
CharacterSprite.tsx: Character animation system
QuestsList.tsx: Task management with Eisenhower matrix
PomodoroPage.tsx: Timer implementation with XP rewards
LoginStreakCard.tsx: Streak tracking system
📄 License
MIT License

🙏 Acknowledgements
Character design inspired by Final Fantasy VII
UI aesthetics inspired by Solo Leveling
Built with ShadCN UI, Tailwind CSS, and React
