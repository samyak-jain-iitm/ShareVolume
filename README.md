# ShareVolume<br>
## 📖 Summary<br>
This project provides a web interface to display the shares outstanding for BlackRock and allows users to dynamically fetch data for other companies using their CIK numbers.<br>
## 📋 Features<br>
- Displays maximum and minimum shares outstanding for BlackRock.<br>
- Dynamically updates data based on user input CIK.<br>
- User-friendly interface with clear visual representation.<br>
## ⚙️ Setup<br>
To run this project locally, clone the repository using the following command:<br>
```
git clone https://github.com/samyak-jain-iitm/ShareVolume
```
Then, open `index.html` in your web browser.<br>
## ▶️ Usage<br>
To view data for BlackRock, simply open the page. To view data for another company, append `?CIK=XXXXXXXXXX` to the URL, replacing `XXXXXXXXXX` with the desired 10-digit CIK number.<br>
## 📝 Code Explanation<br>
The HTML file includes a script that fetches data from the SEC API, processes it to find the maximum and minimum shares outstanding, and updates the DOM elements accordingly.<br>
## 🛠️ Technologies Used<br>
- HTML5<br>
- CSS3<br>
- JavaScript<br>
- Fetch API<br>
## 📜 License<br>
This project is licensed under the MIT License.