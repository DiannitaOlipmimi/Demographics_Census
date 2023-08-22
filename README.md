# Demographics Census - Interactive Dashboard


**⛳Deskripsi Masalah:**

You are working as a Data Analyst for a retail company that sells consumer electronics. The company collects sales data through Google Forms from its retail stores and compiles the information in a Google Spreadsheet. The management team wants to monitor the sales performance in real time to make informed decisions.

**⛳Tujuan:**

You decide to build a real-time dashboard using Looker Studio to provide the management team with instant access to the sales performance data.

## 📌Table of contents
- [Dataset dan Variabel]()
- [Result]()
- [Links]()


## 🧵Data dan Variabel

**📒Data:**

googleform (dapat diisi dan hasilnya akan langsung terupdate pada dashboard setiap 10 detik)

https://forms.gle/uHTJzsKrUbWQw2Aa8

dataset diambil dari spreadsheet yang merupakan hasil respon dari google form dan dummy data

https://docs.google.com/spreadsheets/d/1R_bfoZORHvjIBMkcMhn1uuQNtrND4W8AqEKkUgZqKXI/edit?usp=sharing

**📒Variabel:**

- `Timestamp`: waktu pengisian googleform 
- `Domisili Provinsi`: domisili provinsi pengisian googleform (38 Provinsi di Indonesia)
- `Jenis Kelamin`: jenis kelamin pengisi googleform (Laki-laki/perempuan)
- `Umur (tahun)`: umur pengisi googleform
- `Pendidikan terakhir`: pendidikan terakhir (SD/SMP/SMA/DIPLOMAT/SARJANA/MAGISTER/DOKTORAL)
- `Status Perkawinan`: hubungan pengisi googleform (lajang/menikah)
- `Status Pekerjaan`: jenis pekerjaan
- `gen`: tipe generasi berdasarkan umur

## 🧵Result

Data Collection:

Set up a Google Form to collect sales data, including product sold, quantity, store location, and sales amount.
All form submissions are automatically recorded in a Google Spreadsheet.
Data Integration:

Use Looker's data integration capabilities to connect to the Google Spreadsheet and pull the relevant sales data.
Looker Studio Dashboard Creation:

Log in to Looker Studio and create a new dashboard project.
Design the dashboard layout using Looker's user-friendly interface, arranging various visualizations and data tiles.
Real-Time Data Visualizations:

Build real-time visualizations that automatically update as new data is added to the Google Spreadsheet.
Visualizations could include:
A line chart showing sales trends over time.
A heat map highlighting top-selling products by store location.
A gauge chart displaying the daily sales target progress.
Data Alerts:

Implement data alerts to notify stakeholders when specific conditions are met, such as achieving a sales milestone or falling below a sales target.
Sharing and Access:

Share the Looker Studio dashboard with the management team, providing them with secure access to real-time sales insights.
Enable interactive features like drill-downs and filters to allow users to explore the data on their own.
Outcome:
The real-time sales performance dashboard provides the management team with instant insights into sales trends, product performance, and store-specific data. This enables them to make timely decisions, allocate resources effectively, and take actions based on the most current information available.

Key Skills Demonstrated:

Data integration from Google Forms and Google Spreadsheets.
Dashboard creation and visualization using Looker Studio.
Real-time data updates and alerts for informed decision-making.
Collaboration and communication skills for sharing insights with stakeholders.
Note:
This study case is fictional and created for illustrative purposes. It demonstrates how you might approach building a real-time dashboard using Looker Studio with data from Google Spreadsheet and Google Form sources.

[![Alt text](<Screenshot (1062).png>)](https://lookerstudio.google.com/embed/reporting/b7eb8cf3-a379-4bde-afe2-deb0d6d3a5a0/page/MLVaD)

## 🧵Links

📊 Looker Studio Link





