# Reading Log Project

## My Purpose
I am using this log as part of my homeschooling journey, specifically utilizing the **Discovery K-12** platform without paying for the parent service and keeping track of my kid's daily reading this year. While Google Forms could offer a simpler solution, I wanted to make the process more visually appealing and interactive by adding star ratings and emotional feedback.

## Why You Should Use it Too
This project is a responsive, visually appealing reading log form designed for use with Formspree. It allows students or users to submit their daily reading information, including book details, a rating, and their feelings about the reading. The form integrates custom styling, a star-rating system, and a feelings selector to make the experience interactive and fun.

## Track

- **Book Title**
- **Author**
- **Page Numbers** (Start and End)
- **Summary** of what they've read
- **Interactive Star Rating**
     - Users can select a star rating from 1 to 10 based on their enjoyment
        - JavaScript is used to handle the "fill effect" when stars are clicked.  
       - This creates a visually engaging way for users to rate their books.
- **Feelings**         
  - Users can choose from a list of emotions (e.g., Angry, Happy, Excited) to describe how they felt about the book. 
    - Hover and selection effects are applied to make the interaction more intuitive.

## Formspree Integration  
   - The form action was updated to send data via Formspree. This enables submissions to be emailed directly to a specified email address for FREE (limited to 50 submissions a month on the free plan).  
   - Field names were added to match Formspree's format (name, email, etc.).

## HOW TO USE IT

1. **Clone the repository:** 
    - Copy the repository to your local machine using the `git clone` command.
    - `git clone https://github.com/your-username/reading-log-project.git`
  
      
2. **Create a Formspree Account**
    -Free Version
    -Click "Add New" ---> New Form
    -Copy Form End Point
        ![image](https://github.com/user-attachments/assets/2c3d4cce-6034-4d36-8468-b374b5905b6b)

      
3. **Add Form Endpoint**
    -Paste in in the code.

 ![save formspree](https://github.com/user-attachments/assets/09101e8a-9bad-4182-8473-7ef1776b3ed6)


4. **Test the Form**
After updating the form with the new endpoint, save and test it.
Submit the form to ensure that the responses are sent to your email or dashboard.

![submission](https://github.com/user-attachments/assets/3d8580c7-f755-4593-b378-129fd27cdbde)

## Improvements

### 1. *Formspree Integration*
   - *What was added:* Updated the <form> action attribute to point to Formspree's API endpoint and renamed form field names to use Formspree's naming conventions.  
   - *Why:* To enable email-based form submissions *without requiring a backend server*.  

### 2. *JavaScript for Star Ratings*
   - *What was added:* A script to toggle the "filled" state of stars based on the user’s selection.  
   - *Why:* To make the rating system visually interactive and user-friendly.

### 3. *Improved Accessibility*
   - *What was added:* ARIA attributes (aria-label) for the feelings selector radio buttons and keyboard support for the star ratings.  
   - *Why:* To ensure the form is accessible for all users, including those using screen readers.

### 4. *Enhanced Styling*
   - *What was added:* Hover and focus states for buttons, radio inputs, and stars; better padding and alignment for elements.  
   - *Why:* To provide a polished, professional design that improves user experience.

## Future Improvements

- Add **emotional faces** to the "feelings" section of the form to enhance user interaction and make it even more engaging (not just words that shade to a color when chosen) similar to the pain scale chart.
  
## Contributions

This project is still a **work in progress**, and I may be updating if I find easier solutions or feel inspired.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions, feel free to reach out via email at **educational@technologist.com**.


