CoCoFineArtWebsite/
├── frontend/
|   ├── public/			#static assets like  images
favicon
|   ├── src/			
|   |   ├── components/		# reusable components (ex. buttons, Navbars, Footer)
|   |   ├── pages/			# page components (logins, signups, Dashboard)
LoginSignupPage, etc
|   |   ├── App.js			# Main stucture (root component), aet up routes
|   |   ├── index.js		# entry point, ，將 <App /> 掛入 HTML 中
|   └── package.json		# frontend dependencies 
							# 記錄使用的套件、版本與啟動腳本
|
├── backend/
|   ├── controllers/		# handle requests and responses ex. authController.js, staffController.js
|   ├── models/				# database models ex. User.js, Staff.js, Request.js
|   ├── routes/				# define API endpoints ex. authRoutes.js, staffRoutes.js
|   ├── app.js				# main server logic
|   ├── .env
|
|   ├── database/
|   |   ├── schema.sql		# SQL schema for the database
|   |   ├── seed.sql		# dummy data setup
|
|   ├── docs/
|   |   └── CoCo_User_Diagram.png
|
├── README.md
├── .gitignore
└── package.json / requirements.txt