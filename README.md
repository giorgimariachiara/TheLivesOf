# TheLivesOf


"The Lives” is a metadata-enriched and stylistically customizable magazine about only source about the lives of the most important artists of Florence: “The Lives of the most famous painters, sculptures and architects” of Giorgio Vasari, the eminent Renaissance historian. The project has been developed in the framework of the course “Information Modelling and Web Technologies”, held by Prof Vitali for the MA in “Digital Humanities and Digital Knowledge” in the a. y. 2022/2023. <br>

 The project was carried out by  <a href="https://github.com/giorgimariachiara">Maria Chiara Giorgi</a>, <a href="https://github.com/elizastuglik">Eliza Stuglik</a> and <a href="https://github.com/ghasempouri1984">Ali Ghasempouri</a>. 


### Running the Project Locally for Style Testing

To test the project locally without deploying it on a web server, please follow the steps outlined below.

#### Step 1: Navigate to the Project Directory

Open your terminal (on Unix/Linux/MacOS) or Command Prompt (on Windows) and navigate to the folder where you have cloned or downloaded the repository.

For example, if your folder is located in `C:\Github\thelivesof`, you can navigate there by executing:
```bash
cd C:\Github\thelivesof
```

#### Step 2: Start a Local HTTP Server

Once you are in the project directory, execute the following command to start a local HTTP server:
```bash
python -m http.server 8000
```

This will start a local HTTP server on port 8000.

#### Step 3: Access the Project in a Web Browser

Open your web browser and navigate to the following address:
```
http://localhost:8000
```

You should now see the home page of the project. Feel free to navigate through the website to test the JavaScript functions responsible for maintaining user-selected styles.
