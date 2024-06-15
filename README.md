# JoSAA DATA ANALYSIS PORTAL 
<br><br>

<body>
    <h1>JOSAA Seat Allotment Portal</h1>
    <p>This project aims to create a portal to explore the seat allotment statistics of the Joint Seat Allocation Authority (JOSAA) until 2023. The portal allows users to analyse the data and provides insights and visualisations based on the JOSAA seat allotment data from 2016 to 2023.</p>
    
    <h2>Goals</h2>
    <ol>
        <li>Perform data cleaning and exploratory data analysis (EDA) on the JOSAA seat allotment data.</li>
        <li>Create a SQLite database from the cleaned data and perform queries on it.</li>
        <li>Develop a website to present the analysis using various charts and tables.</li>
    </ol>
    
    <h2>Tech Stack/Frameworks</h2>
    <ul>
        <li><b>Frontend:</b> HTML, CSS, JavaScript</li>
        <li><b>Backend:</b> Django, SQLite</li>
        <li><b>Data Scraping:</b> Selenium</li>
        <li><b>Data Cleaning:</b> NumPy, Pandas</li>
        <li><b>Visualisation:</b> Chart.js</li>
    </ul>
    
    <h2>Usage</h2>
    <p>To run the JOSAA Seat Allotment Portal locally, follow these steps:</p>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/your-username/josaa-portal.git</code></pre>
        </li>
        <li>Change to the project directory:
            <pre><code>cd josaa-portal</code></pre>
        </li>
        <li>Install the required Python packages:
            <pre><code>pip install -r requirements.txt</code></pre>
        </li>
        <li>Run database migrations:
            <pre><code>python manage.py migrate</code></pre>
        </li>
        <li>Start the development server:
            <pre><code>python manage.py runserver</code></pre>
        </li>
        <li>Access the portal in your web browser at <a href="http://localhost:8000/">http://localhost:8000/</a>.</li>
    </ol>
    
    <h2>Data Extraction and Cleaning</h2>
    <p>The JOSAA seat allotment data has been provided and is ready for analysis. The data cleaning process involves using the NumPy and Pandas libraries to clean and transform the data as required for analysis.</p>
    
    <h2>Data Analysis and Insights</h2>
    <p>The portal offers several sections for in-depth data analysis:</p>
    <ul>
        <li>Round-wise Trends: Check the opening and closing ranks for all six rounds for a particular year.</li>
        <li>Year-wise Trends: Examine the opening and closing ranks from 2016-2023 for a specific round.</li>
        <li>Top 20 Courses: Discover the top 20 courses suitable for you based on your achieved rank.</li>
        <li>Course Comparison: Compare two courses from the same or different colleges and assess their popularity.</li>
        <li>Best College: Identify the best colleges based on their popularity for a particular course.</li>
        <li>Category-wise Analysis: Analyse the category-wise differences between opening and closing ranks.</li>
    </ul>
    
    <h2>Final Output</h2>
    <p>When running this project on local servers, you can analyse the data based on various trends in the sections mentioned above.</p>
    
    <h2>Output Files</h2>
    <p>In the Outputs (images & video) folder, you will find some graph images and a video showcasing the working project.</p>
    
    <h2>Contributions</h2>
    <p>Contributions to this project are welcome! If you have any suggestions, improvements, or new features to add, please open an issue or submit a pull request.</p>
    
    <h2>Acknowledgements</h2>
    <p>This project utilises several open-source libraries and frameworks:</p>
    <ul>
        <li>Django</li>
        <li>Selenium</li>
        <li>Pandas</li>
        <li>NumPy</li>
        <li>Chart.js</li>
    </ul>
    <p>We extend our heartfelt thanks to the developers of these tools for their invaluable contributions to the open-source community.</p>
    <p>This project was made possible thanks to the support and allocation of this summer project by the Coding Club, IIT Guwahati.</p>
    
    <h2>Contributors</h2>
    <ul>
        <li>Debabrata Samanta, MSc Mathematics</li>
        <li>Pratham Doiphode, MSc Mathematics and Computing</li>
        <li>Priyanshu Kumar, MSc Mathematics</li>
        <li>Sourish Maity, MSc Mathematics and Computing</li>
    </ul>
    
    <p>Thank you for visiting the JOSAA Seat Allotment Portal. We hope you find this resource insightful and useful in your academic and research endeavours.</p>
</body>

