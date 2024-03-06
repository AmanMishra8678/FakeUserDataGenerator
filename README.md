# FakeUserDataGenerator
Fake User Data Generator
This Python script generates fake user data using the Faker library and provides options to save the data to CSV, TXT, or both file formats.

Usage
Clone the repository:
bash
Copy code
git clone https://github.com/AmanMishra8678/FakeUserDataGenerator.git
cd FakeUserDataGenerator
Install the required dependencies:
bash
Copy code
pip install faker
Run the script:
bash
Copy code
python fake_user_data_generator.py
Follow the prompts to input the number of users to generate and choose whether to save the data to a file.
Functions
generate_user_data(num_of_users)
Generates fake user data with the specified number of users.

save_to_csv(data, filename)
Saves user data to a CSV file.

save_to_text(data, filename)
Saves user data to a text file.

print_data_vertically(data)
Prints user data vertically.

How to Save Data
If you choose to save the data:

Specify the file type (CSV, TXT, or both).
Enter the desired filenames (without extensions).
If you choose not to save the data, it will be printed vertically.

Note
Ensure you have the Faker library installed before running the script (pip install faker).
Feel free to use this script for generating test data or for any other purposes.
Contributions and feedback are welcome!
