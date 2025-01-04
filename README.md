# Reading Log Project

## Overview

This project is a **Reading Log** created to help track my kids' reading progress. The goal is to keep a fun and engaging log of their daily reading that is stored digitally and for free, including:
- **Book Title**
- **Author**
- **Page Numbers** (Start and End)
- **Summary** of what they've read
- **Rating** (1-10 stars) based on their enjoyment
- **Emotions** they felt while reading (Happy, Excited, Neutral, etc.)

## Purpose

I am using this log as part of my homeschooling journey, specifically utilizing the **Discovery K-12** platform without paying for the parent service. While Google Forms could offer a simpler solution, I wanted to make the process more visually appealing and interactive by adding star ratings and emotional feedback.

## Key Features

- **Interactive Form**: The log includes an engaging form where students can rate their reading with stars (like on Amazon where they turn yellow/gold when selected) 
- **Customizable**: - Expand the grade options and form fields for additional customization. You can easily change the grade levels to fit your needs. Currently, I have options for 4th and 5th grades.
- **Free Data Storage**: I am currently working on using **Formspree** to collect the form submissions and store the data via email for free.

## How to Use

1. **Clone the Repository**:
    - Copy the repository to your local machine using the `git clone` command.
    - `git clone https://github.com/your-username/reading-log-project.git`
2. **Change the Form Endpoint**

This project uses **Formspree** (free version) to handle form submissions and send them directly to a dedicated email address. This helps me keep track of the reading records for this year’s Discovery K-12.

*If you'd like to use Formspree for your own form submissions, follow these steps to change the form's endpoint:*

   -   Create an account or log into your existing Formspree account.
   -   Copy the new form submission URL (endpoint) provided by Formspree.
   -   Replace the existing action URL in your HTML form with the new URL you copied.

Once updated, your form will start sending data to the new email address connected to your Formspree account.

3. **Test the Form**
After updating the form with the new endpoint, save and test it.
Submit the form to ensure that the responses are sent to your email or dashboard.

## Future Improvements

- Add **emotional faces** to the "feelings" section of the form to enhance user interaction and make it even more engaging (not just words that shade to a color when chosen).


## Contributions

This project is still a **work in progress**, and may be updating if I find easier solutions or feel inspired.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions, feel free to reach out via email at **educational@technologist.com**.
