
# Python Web Homework 8

This project demonstrates the use of RabbitMQ for message queues, MongoDB as a database, and simulates the process of sending emails and SMS to contacts.

## Installation

1. Ensure you have RabbitMQ and MongoDB set up and running.
2. Clone this repository:
   ```bash
   git clone https://github.com/leegosx/py-web-hw8.git
   ```
3. Navigate to the project directory:
   ```bash
   cd py-web-hw8
   ```
4. (Optional) Set up a virtual environment and activate it.
5. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the producer script to generate fake contacts and queue them for processing:
   ```bash
   python producer.py
   ```
2. Run the consumer scripts to process and simulate sending emails or SMS:
   ```bash
   python consumer_email.py
   python consumer_sms.py
   ```

## Features

- Generates fake contacts with emails and phone numbers.
- Uses RabbitMQ to manage queues for email and SMS notifications.
- Simulates the process of sending emails and SMS.

## Contributors

- [Dmytro](https://github.com/leegosx)

## License

This project is open source and available under the [MIT License](LICENSE).
