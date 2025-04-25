Steps for execution:
open Integrated terminal for frontend and backend seperately and execute the below commands

frontend and backend: (execute these commands parallely)
npm install
npm run dev (if errors)
fix:
npm install --save-dev nodemon
rm -rf node_modules package-lock.json
npm cache clean --force
npm install
npm install --save-dev nodemon

Follow the link local host link: http://localhost:5173/signin