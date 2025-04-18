CoCoFineArtWebsite/
�u�w�w frontend/
|   �u�w�w public/			#static assets like  images
favicon
|   �u�w�w src/			
|   |   �u�w�w components/		# reusable components (ex. buttons, Navbars, Footer)
|   |   �u�w�w pages/			# page components (logins, signups, Dashboard)
LoginSignupPage, etc
|   |   �u�w�w App.js			# Main stucture (root component), aet up routes
|   |   �u�w�w index.js		# entry point, �A�N <App /> ���J HTML ��
|   �|�w�w package.json		# frontend dependencies 
							# �O���ϥΪ��M��B�����P�Ұʸ}��
|
�u�w�w backend/
|   �u�w�w controllers/		# handle requests and responses ex. authController.js, staffController.js
|   �u�w�w models/				# database models ex. User.js, Staff.js, Request.js
|   �u�w�w routes/				# define API endpoints ex. authRoutes.js, staffRoutes.js
|   �u�w�w app.js				# main server logic
|   �u�w�w .env
|
|   �u�w�w database/
|   |   �u�w�w schema.sql		# SQL schema for the database
|   |   �u�w�w seed.sql		# dummy data setup
|
|   �u�w�w docs/
|   |   �|�w�w CoCo_User_Diagram.png
|
�u�w�w README.md
�u�w�w .gitignore
�|�w�w package.json / requirements.txt