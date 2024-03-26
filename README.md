# Hotel Booking Bot with Amazon Lex

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Steps](#steps)
- [Additional Notes](#additional-notes)
- [Testing the Chatbot](#testing-the-chatbot)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This guide demonstrates how to create a hotel booking bot using Amazon Lex. Follow the steps below to set up your bot on the AWS Management Console.

## Prerequisites

Before you begin, ensure you have:

- An AWS account.
- Access to the AWS Management Console.

## Steps

1. Navigate to [AWS Management Console](https://aws.amazon.com/console/).
2. Login to your Amazon Web Services portal.

   ![Alt Text](Instructions/1.png)

   ![Alt Text](Instructions/2.png)

4. Click the "Search" field and type "lex".

   ![Alt Text](Instructions/3.png)
   
5. Click "Amazon Lex".
   
   ![Alt Text](Instructions/4.png)

6. Click "Create bot".

   ![Alt Text](Instructions/5.png)

8. Choose "Create a blank bot" or "Create a basic bot".

   ![Alt Text](Instructions/6.png)

10. Enter the name for your bot in the "Bot name" field. Example: "Hotelbooking".

    ![Alt Text](Instructions/7.png)

12. Optionally, enter a description for your bot.

    ![Alt Text](Instructions/8.png)

14. Click "No" for the "Childrens Online Privacy  Protection Act (COPPA)"

    ![Alt Text](Instructions/9.png)

16. select "Create a role with basic Amazon Lex permissions." option.

    ![Alt Text](Instructions/10.png)
    
18. Click "Next" and then "Done".    

19. Click the "Intent name" field and enter an intent name.

    ![Alt Text](Instructions/11.png)
    
21. Click on Initial response and add message

    ![Alt Text](Instructions/17.png)

23. Add utterances by clicking "Add utterance" and typing phrases such as "Hi", "I want to book a hotel", "Can you help me to book a room?".

    ![Alt Text](Instructions/12.png)

25. For each utterance, add corresponding messages in the "Message - optional" field.

    ![Alt Text](Instructions/14.png)

27. Add slots for capturing user inputs, such as first name, last name, check-in date, etc.

    ![Alt Text](Instructions/22.png)

29. Define prompts for each slot to ask the user for input.

30. Configure "In case of failure" and "On successful fulfillment" responses.

    ![Alt Text](Instructions/25.png)

    ![Alt Text](Instructions/25.png)

32. Add a confirmation prompt and closing response.

    ![Alt Text](Instructions/27.png)

34. Click "Save intent".

    ![Alt Text](Instructions/31.png)

36. Click "Build" and then "Test" to test your bot.

    ![Alt Text](Instructions/32.png)

38. Once the bot is ready for complete testing, proceed with testing.

    ![Alt Text](Instructions/33.png)

    ![Alt Text](Instructions/34.png)

    ![Alt Text](Instructions/35.png)

    ![Alt Text](Instructions/36.png)

## Additional Notes

For more detailed instructions and troubleshooting tips, refer to the [AWS Lex Documentation](https://docs.aws.amazon.com/lex/).

## Testing the Chatbot

Once your bot is built and configured, it's essential to thoroughly test it to ensure it behaves as expected. Follow these steps to test your chatbot:

1. Initiate a conversation with the bot by typing messages or utterances.
2. Provide inputs for the bot's prompts and slots to simulate user interactions.
3. Verify that the bot responds correctly to different scenarios and inputs.
4. Identify any errors or unexpected behavior and make necessary adjustments to the bot's configuration.
5. Continue testing until the bot performs satisfactorily in various test cases.
6. For detailed PDF version kindly check this [folder](/PDF/HotelBookingBot.pdf)

For more detailed instructions and troubleshooting tips, refer to the [AWS Lex Documentation](https://docs.aws.amazon.com/lex/).

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
