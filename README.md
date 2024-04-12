# Installing Barangay South Signal Village Web App Project from a Cloned Repository

1. **Clone the Repository**: First, navigate to the directory where you want to store your project and clone the repository using Git. Run the following command in your terminal:
   ```bash
   git clone <repository_url>

2. **Install Composer**: Laravel uses Composer to manage its dependencies. If you haven't installed Composer yet, download and install it from [getcomposer.org](https://getcomposer.org/download/).

3. **Navigate to Project Directory**: Once the repository is cloned, navigate to the project directory using the `cd` command:
   ```bash
   cd your_project_name
   
4. **Install Dependencies**: Use Composer to install the project dependencies by running:
   ```bash
   cd composer install
   
5. **Create Environment File**: Laravel requires an environment file to store configuration variables. Copy the `.env.example` file to create a new `.env` file:
      ```bash
   cp .env.example .env
6. **Generate Application Key**: Laravel requires an application key for encryption. Generate a new application key using the `artisan` command:
      ```bash
   php artisan key:generate
 
7. **Set Up the .env**:  Open the .env file in a text editor and configure the database connection settings
   
9. **Import the existing dbs**:Create a barangay table in your MySQL PHP Admin. Inside the barangay table, import the provided barangay file. The barangay file can be found in Teams.
   
10. **Serve the Application**: Finally, you can serve the Laravel application locally using the `artisan` command:
   ```bash
  php artisan serve
