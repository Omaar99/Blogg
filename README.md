# Blog
# Laravel Project: [Your Project Name Here]

This is a new Laravel project.

## Getting Started

These instructions will guide you through setting up the project on your local machine for development and testing purposes.

### Prerequisites

* PHP >= 8.1
* Composer
* Node.js and npm (or yarn)
* MySQL (or another database of your choice)
* Git

### Installation

1.  **Clone the repository:**

    ```bash
    git clone :  https://github.com/Omaar99/Blogg
    cd Blogg
    ```

2.  **Install Composer dependencies:**

   
    composer install
  

3.  **Copy the `.env.example` file to `.env` and configure your environment:**

    
    cp .env.example .env
    

    * Open `.env` and update the database connection details (DB\_DATABASE, DB\_USERNAME, DB\_PASSWORD).
    * Generate an application key:

      
        php artisan key:generate
    

4.  **Install Node.js dependencies:**

    
    npm install # or yarn install


5.  **Compile assets:**

   
    npm run dev # or yarn dev
    

6.  **Run database migrations:**

    php artisan migrate
 

7.  **(Optional) Seed the database:**

    
    php artisan db:seed
    

8.  **Start the development server:**

    php artisan serve
    
    The application will be available at `http://127.0.0.1:8000`.

## Development

* Make changes to your code in the `app` directory.
* Use `npm run watch` (or `yarn watch`) to automatically compile assets during development.
* Run tests using `php artisan test`.

## Deployment

Instructions for deploying your application to a production environment will vary depending on your hosting provider. See the Laravel documentation for deployment best practices.

## Contributing

Please read `CONTRIBUTING.md` for details on how to contribute to this project.

## License

This project is licensed under the [MIT License](LICENSE.md) - see the `LICENSE.md` file for details.
