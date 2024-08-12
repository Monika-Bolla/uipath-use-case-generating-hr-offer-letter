# UiPath HR Offer Letter Automation

# Use Case Overview

This project automates the process of generating and sending HR offer letters using UiPath. The process involves the following stages:

1. Dispatcher

- **Filter Hired Candidates**: The Dispatcher component filters the list of candidates who have been hired and need an offer letter.
- **Add to Queue**: The filtered candidates are then added to a queue for processing.

 2. Performer

- **Update Offer Letter Template**: The Performer component retrieves the offer letter template and populates it with the candidate's details from the queue.
- **Save as PDF**: The updated offer letter is saved as a PDF file.
- **Store in Offer Letter Folder**: The generated PDF file is stored in a designated folder for offer letters.
- **Send Email**: An email is sent to the candidate with the offer letter attached.

 Getting Started

1. **Prerequisites**:
   - UiPath Studio installed on your machine.
   - Access to the necessary templates and email configuration.

2. **Setup Instructions**:
   - Clone the repository using `git clone <repository-url>`.
   - Open the project in UiPath Studio.
   - Configure the necessary settings, including email credentials and file paths.

3. **Usage**:
   - Run the Dispatcher workflow to filter and queue candidates.
   - Execute the Performer workflow to generate and send offer letters.

# Contact

For any questions or support, please contact [bmonika0129@gmail.com].
