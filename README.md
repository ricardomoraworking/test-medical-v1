<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>


## Nu Image Medical Test Project

We want you to build a contact form with just a few requirements listed below. It should only take a 2-3 hours to complete. It’s a very simple project, so there is room to put work into the details:

Start with a brand-new Laravel 9.x project
Build the form as a Vue component that submits via AJAX to the Laravel backend
It should have the following fields: name, email, phone, question/comments
TDD the backend endpoint
Save the submissions to the database

Send a markdown-based email to a support email after the submission is saved

Other than those requirements, you can build the project anyway you would like.Bonus points for using Tailwind CSS and handling validation errors on the frontend.When finished, create a repository on GitHub, Bitbucket, or Gitlab and send us a link.Please get this back to us in one business day. If you need more time, please let us know.

## Solution

1. Repository is created on Github. for simplicity of the test we will only use 2 branches (dev, main)
2. A project was created in Laravel 9, following the specifications.
3. For the integration with vue, due to time issues and preventing version problems, Inertia will be used.
4. The integrated version Sqlite will be used for the BD solution
5. Migrated to Axios due to initial requirements
6. tests added for validate endpoint, and the render of the register view.

## Results

Form:
![Screenshot 2023-05-22 at 7 06 20 PM](https://github.com/ricardomoraworking/test-medical-v1/assets/107133350/f0d22b18-5e7c-4b25-87d4-a4f32285c7fa)

BD Data:
![Screenshot 2023-05-22 at 7 07 27 PM](https://github.com/ricardomoraworking/test-medical-v1/assets/107133350/fa565bec-2989-45d2-8945-41c72054aebe)

Test
![Screenshot 2023-05-22 at 7 31 25 PM](https://github.com/ricardomoraworking/test-medical-v1/assets/107133350/8a5d09e8-cb75-49c2-8bb0-e6c0d1daa281)

TimeDev
![Screenshot 2023-05-22 at 7 31 56 PM](https://github.com/ricardomoraworking/test-medical-v1/assets/107133350/ed39bd4f-63df-48b4-94a4-762201c4d37d)


## Limitations
1. The time to make the septup of the environment 
2. Some time, without doing laravel, I have been in projects with React, graphql, and node lately, but I consider that I catch up quickly between languages
