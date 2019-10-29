# MediTechSafe UI Design for ABC Company
The Dashboard and Equipment page layout were designed as  per the requirements.

## Getting Started

These instructions will get you a copy of the project up and running on your machine for development and testing purposes. 

### Prerequisites

	BootStrap from get-bootstrap.com
  NodeJS
  Angular 8 
  Angular CLI from cli.angular.io
	
	Libraries:

	1. Angular Material
	2. 	Charts Module 

Commands:

	$ npm install -g @angular/cli  
	$ ng new MeditechSafe
	$ ng generate component
	$ ng serve -o


### How to run

	Inside the project directory run the cmd command to set up the localhost server, ng serve on port 4200 and the browser opens with the UI designed pageon it.
	
	.................
	$ User/MediTechSafe/Project/ ng serve -o
	.................	


### Design Details:


  1.app-routing.module.ts - Path and Component are defined.
  2.Index.html     - Main HTML with the HTML5 Doc Type
	3.app.component.html - Index file from which al the other compoonents are referred.
  4.module.ts- Imports all the angular material libraries for navbar and charts. 
  5.Dashboard Component has it's own html and module.ts component referenced to  app.component.html
  6.Department-List Component also has it's own html and module.ts component referenced to  app.component.html
  
  
  ### Abstract
  
  The src folder has all the app and different components with their .html,.ts and .css files inside it.
	


## License
MIT License

Copyright (c) [2019] [Aravind Sankar]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
