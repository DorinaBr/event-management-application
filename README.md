# Event Management Application

An application to manage event details, registrations and notifications.

### How to use

- Access http://localhost:8080/swagger-ui/index.html
- Create an organizer
- Create an event with the organizer id set at the previous step
- Create a participant with:
    - valid email address (an email will be sent to it)
    - valid phone number which must be verified by Twilio
            - sign up at https://www.twilio.com/try-twilio
      
            - verify your phone number
- Create a notification
    - you can choose to write your custom message or leave that field empty which will generate a default message
    - after executing the notification creation, a SMS will be sent to your phone number
- You can perform Update and Delete operations
   
### The team

- [Dorina Brahasteanu](https://github.com/DorinaBr)
- [Gabriel Florentin Pascu](https://github.com/GabiPascu)
- [Robert-Daniel Dragomir](https://github.com/robertt287)
- [Luigi Galbenu](https://github.com/luigi13galbenu)