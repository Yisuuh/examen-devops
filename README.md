# Install WordPresss and Configure Pluggins

## WordPress and dependencies
- This docker-compose install 

## Users and Passwords to change in docker-compose.yml file
- MYSQL_ROOT_PASSWORD: password
- MYSQL_PASSWORD: wordpress


### Run locally using docker

1. copy docker-compose.yml to your Install directory

2. Run the containers

docker compose up

3. Stop the instances

docker compose down

# Step 1) Run WordPresss and Configure

- http://localhost:8000/
- Configure Site Title e.g. WCMX
- Username e.g. admin
- Password e.g. 123456 
- Confirm Password checked
- Press Install Button

![WordPress-Screen01](imgs/01WP_Install.png)

# Step 2)Login WordPresss 

- Press Log In button

![WordPress-Screen02](imgs/02WP_Install.png)

# Step 3) Login WordPresss with Username and Password

- Login with Username admin
- Password 123456 

![WordPress-Screen03](imgs/03WP_Install.png)

# Step 4) Select Pluggins Menu

- Select Option Pluggins

![WordPress-Screen04](imgs/04WP_DeletePluggins.png)

# Step 5) Add Pluggins

- Add Pluggin Guttentor 
- Select Guttentor pluggin and press Install Now

![WordPress-Screen05](imgs/05WP_AddPluggins.png)

# Step 6) Add Pluggins

- Add Pluggin Classic Editor
- Select Button Activate

![WordPress-Screen06](imgs/06WP_AddPluggins.png)

# Step 6) Add Pluggins

- Add Pluggin Addons for Gutenberg
- Select Instal Now
- Select Button Activate

![WordPress-Screen07_2](imgs/07_2WP_AddPluggins.png)


# Step 7) Configure Block editor

- Select Settings
- Choose Block editor
- Button Save Changes

![WordPress-Screen07_3](imgs/07_3WP_AddPluggins.png)

# Step 8) Add a Theme

- Select Appereance Menu
- Choose Add New Theme
- Search Ample Bussiness Epic
- Add Theme

![WordPress-Screen07](imgs/07WP_AddPluggins.png)

# Step 8) Import a Page

- Menu Tools
- Select Upload file and import
- Choose wcmx.WordPress.2020-08-10.xml file


![WordPress-Screen08](imgs/08Import.png)

# Step 9) Edit Post

- This import the example page but not the media (images)

![WordPress-Screen09](imgs/09Import.png)


# Step 10) Edit Post

- Select Posts Menu
- Select Test 2 Post

![WordPress-Screen10](imgs/10EditPosts.png)


# Step 11) Add Media to Post 2

- Select Post and Button Edit Image
![WordPress-Screen11](imgs/11WP_AddPhotos.png)

- Upload images carrusel01-1.jpg carrusel02.jpg carrusel03.jpg
![WordPress-Screen12](imgs/12WP_AddPhotos.png)

- Select image for other post
![WordPress-Screen13](imgs/13WP_AddPhotos.png)



