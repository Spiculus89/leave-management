<h1 align="center">Welcome to leave-management 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://twitter.com/alibegovic89" target="_blank">
    <img alt="Twitter: alibegovic89" src="https://img.shields.io/twitter/follow/alibegovic89.svg?style=social" />
  </a>
</p>

> This project is a leave management application for WalterCode employees, built using Node.js, Express framework with a MongoDB database on the backend. On the frontend I used ReactJs, TailwindCss for UI and Redux for state management. 
Users must register with the application by providing basic information, including a WalterCode email address and password. The system supports two user roles: admin and employee. If the email sent in the registration process is admin@waltercode.com, the user is assigned an admin role, otherwise, they are assigned an employee role.

Employee users can apply for leave by providing information including reason for leave, leave type (vacation, sick, or other), start and end dates of leave. By default, leave requests are set to the Pending state. Users can update or delete all applied leaves that are in the Pending state. Users can only view their own leave requests, regardless of the state.

Administrator users can retrieve information about all leave requests. All results will be ordered by the date of creation. Administrators can change the state of leave requests from Pending to Approved or Cancelled. Additionally, the system provides an option for administrators to create a report that groups by user and summarizes all Approved leaves for a specified time period.

An administrator user will be automatically created if one does not exist when the application starts.

## Install

```sh
npm install on both client and server folders
```

## Author

👤 **Amar Alibegovic**

* Website: https://portfolio-ftq8ubrgq-spiculus89.vercel.app/
* Twitter: [@alibegovic89](https://twitter.com/alibegovic89)
* Github: [@Spiculus89](https://github.com/Spiculus89)
* LinkedIn: [@amar-alibegovic-71728b138](https://linkedin.com/in/amar-alibegovic-71728b138)

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_