# E-Commerce Web Application Testing
**Overview**

This project focuses on end-to-end manual test case design and functional validation for an E-commerce website that supports user registration, login, product listing, filtering, and shopping cart functionality.

It simulates real-world test scenarios a QA Engineer would execute on a retail web platform. The test cases cover both positive and negative flows across different modules.

**Scope of Testing**

- User Registration
- User Login
- Product Search and Filters
- Product Listing & Pagination
- Add to Cart
- Navigation and Links
- UI/UX Validations

**Tools Used**

- Microsoft Excel: Test Case Documentation
- Browser DevTools: Manual Testing

**Key Test Modules & Coverage**
- Registration Module\
Validated all fields including name, email, phone, occupation, gender, password.\
Checked for field-level validations and error messages.\
Verified successful form submission and redirection.
- Login Module\
Covered various combinations of correct/incorrect credentials.\
Verified masking of password and redirection after login.\
Checked "Forgot Password" and "Register" link navigation.
- Product Search and Filters\
Search functionality with exact, partial, and invalid input.\
Filter by price range, category, sub-category, gender.\
Boundary conditions like empty filters, min > max price.
- Product Listing & Cart\
Validated product details like image, title, price.\
Checked "View" and "Add to Cart" button functionality.\
Pagination working when more than 9 products are displayed.
- Navigation & UI\
Header navigation tested for redirection to Home, Orders, Cart, and Sign Out.\
Layout and responsiveness verified across different viewports.
