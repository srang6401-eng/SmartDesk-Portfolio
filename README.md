# SmartDesk-Portfolio
A portfolio project demonstrating an ASP.NET Core MVC support request management system. 5.
# SmartDesk | سامانه مدیریت درخواست‌های پشتیبانی

**SmartDesk** یک سامانه تحت وب برای مدیریت درخواست‌های پشتیبانی مشتریان است که با ASP.NET Core MVC توسعه داده شده است.

این سیستم به مشتریان امکان ثبت و پیگیری درخواست‌ها را می‌دهد. کارشناسان پشتیبانی می‌توانند درخواست‌های ارجاع‌شده به خود را مدیریت کنند و مدیر سیستم نیز بر کل فرایند پشتیبانی نظارت دارد.

**دموی آنلاین:** [مشاهده SmartDesk](Demo coming soon)

---

## امکانات پروژه

- احراز هویت و مدیریت کاربران با ASP.NET Core Identity
- کنترل دسترسی مبتنی بر نقش (Role-Based Authorization)
- مدیریت مشتریان و کارشناسان پشتیبانی
- ثبت، مشاهده و پیگیری درخواست‌های پشتیبانی
- ارجاع درخواست‌ها به کارشناسان
- مدیریت وضعیت درخواست‌ها
- ثبت تاریخچه تغییر وضعیت‌ها و کاربر انجام‌دهنده تغییر
- جست‌وجو، فیلتر و صفحه‌بندی درخواست‌ها
- داشبورد و گزارش‌های آماری
- نمودارهای آماری با Chart.js
- تنظیمات سیستم و حالت تعمیر و نگهداری
- محدودسازی دسترسی کاربران به اطلاعات مجاز خود

## نقش‌های کاربری

| نقش | دسترسی‌ها |
|---|---|
| Admin | مدیریت کامل سیستم، مشتریان، کارشناسان، درخواست‌ها، گزارش‌ها و تنظیمات |
| User | ثبت و مشاهده درخواست‌های شخصی |
| SupportAgent | مشاهده درخواست‌های ارجاع‌شده به خود و تغییر وضعیت آن‌ها |

## تکنولوژی‌های استفاده‌شده

- C#
- ASP.NET Core MVC (.NET 8)
- Entity Framework Core 8
- Microsoft SQL Server
- ASP.NET Core Identity
- LINQ
- Bootstrap
- JavaScript
- Chart.js

## مفاهیم فنی پیاده‌سازی‌شده

- معماری MVC
- Dependency Injection
- ارتباطات و روابط پایگاه داده با Entity Framework Core
- مدیریت Migrationها
- احراز هویت و مجوزدهی مبتنی بر نقش
- اعتبارسنجی سمت سرور
- محدودسازی دسترسی بر اساس مالکیت اطلاعات
- صفحه‌بندی و فیلتر اطلاعات
- Memory Caching
- تراکنش‌های پایگاه داده
- مدیریت خطا و حالت تعمیر و نگهداری

## دموی آنلاین

برای مشاهده و بررسی عملکرد سیستم می‌توانید از لینک زیر استفاده کنید:

**دموی آنلاین:** [مشاهده SmartDesk](Demo coming soon)

این نسخه برای نمایش امکانات و تجربه کار با سامانه در نظر گرفته شده است.

---

## English

# SmartDesk | Support Request Management System

**SmartDesk** is a web-based support request management application developed using ASP.NET Core MVC.

The system allows customers to submit and track support requests, support agents to manage their assigned requests, and administrators to oversee the entire support workflow.

**Live Demo:** [View SmartDesk](Demo coming soon)

## Features

- User authentication with ASP.NET Core Identity
- Role-based authentication and authorization
- Customer and support agent management
- Support request creation and tracking
- Request assignment to support agents
- Request status management
- Request status history and change tracking
- Search, filtering, and pagination
- Role-based dashboards
- Statistical reports and charts using Chart.js
- System configuration and maintenance mode
- Ownership-based access restrictions

## User Roles

| Role | Permissions |
|---|---|
| Admin | Full access to system management, customers, agents, requests, reports, and settings |
| User | Create and view personal support requests |
| SupportAgent | View assigned requests and update their statuses |

## Technologies

- C#
- ASP.NET Core MVC (.NET 8)
- Entity Framework Core 8
- Microsoft SQL Server
- ASP.NET Core Identity
- LINQ
- Bootstrap
- JavaScript
- Chart.js

## Technical Implementation

- MVC Architecture
- Dependency Injection
- Entity Framework Core relationships and migrations
- Role-based authentication and authorization
- Server-side validation
- Ownership-based resource authorization
- Pagination and filtering
- Memory Caching
- Database transactions
- Error handling and maintenance mode

## Live Demo

Explore the application using the following link:

**[Open SmartDesk Live Demo](Demo coming soon)**

The live version is provided for demonstration and evaluation purposes.

---

## Project Purpose

SmartDesk was developed as a portfolio project to demonstrate practical skills in ASP.NET Core MVC, Entity Framework Core, SQL Server, Identity, database design, and secure role-based web application development.
