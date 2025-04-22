# Complexity-Measuring-Tool-SPM
For this program, we have created a web application. For this purpose, we have chosen to build this application in Java, Servlet, JSP and Materialize CSS. Due to its versatility in file reading, we choose Java and choose JSP and Materialize CSS with Google fonts to model our software. It is comparatively easy to create simple interfaces using JSP and Materialize CSS than to model the website manually.NetBeans is the IDE we have selected. Netbeans has a multi-language editor, debugger, profiler, control of versions, and collaboration with developers. And it offers parallel support for the GlasshFish server. We use commons-fileupload-1.3.1.jar, org.apache.commons.io.jar (ref[1],[2]) to upload a file from local storage as an external library. GlashFish server should be running on the background to run our program. Otherwise, it won't start the application. The application can be run on a browser and asking for the location of the file will show the main UI. As a string output, the device takes the file location and the Java buffer reader reads the file line by line. The length of each row is determined simultaneously under the four factors. The tool's key four variables are known to be four major classes.

Based on the requirements we implemented complexity measuring tool mainly focusing on four factors. 1.Size 2.Type and the nesting level of control structures 3.Inheritance 4.Recursion

Our system has four main packages of three packages containing java codes to calculate the complexity of a program statement due to type of control structures(CTC), due to nesting of control structures(CNC), due to inheritance(CI), due to size(CS), and another package contains segment of file uploader. There are two classes to measure the CS. Measuring_Complexity_Size.java and Main.java in measuring_complexity_size package. To calculate the CNC, CTC there are two classes namely CNC.java and CTC.java in Fasrin_CTCandCNC. To calculate CI there are two classes Inheritance.java, MainInheri.java in inheritance package.

References
[1] commons-fileupload-1.3.1.jar
 https://mvnrepository.com/artifact/commons-fileupload/commons-fileupload/1.3.1
[2] org.apache.commons.io.jar
https://mvnrepository.com/artifact/commons-io/commons-io/2.4


![Main UI](https://user-images.githubusercontent.com/38991771/66256530-489ab380-e7ac-11e9-8bc6-0d8db35dc158.png)


# 🧠 Complexity Measuring Tool – SPM Project

A web application developed using **Java**, **Servlets**, **JSP**, and **Materialize CSS** to evaluate software code complexity based on four major factors:

1. **Size (CS)**  
2. **Type and Nesting of Control Structures (CTC & CNC)**  
3. **Inheritance (CI)**  
4. **Recursion**

---

## 📌 Features

- 📥 Upload a Java source file for complexity analysis
- 📊 Calculates and displays complexity scores for each line of code
- 📂 Follows a modular Java package structure:  
  - `measuring_complexity_size/` for size-related calculations  
  - `inheritance/` for inheritance complexity  
  - `Fasrin_CTCandCNC/` for control structure and nesting metrics
- 📄 Displays detailed output via web interface styled with **Materialize CSS**
- 🧩 Supports GlassFish deployment (Tested in NetBeans)

---

## 🛠️ Tech Stack

| Layer        | Tools & Technologies                  |
|--------------|----------------------------------------|
| Backend      | Java, Servlets, JSP                   |
| Frontend     | Materialize CSS, HTML5, JavaScript    |
| File Upload  | Apache Commons FileUpload, Commons IO |
| Deployment   | GlassFish Server, NetBeans IDE        |

---

## 🚀 How to Run

1. Open the project in **NetBeans IDE**
2. Ensure **GlassFish server** is configured and running
3. Deploy the web app via NetBeans and access it via browser
4. Upload a `.java` file to view complexity metrics

---

## 📂 Repository Link

- 🔗 [GitHub Repository](https://github.com/fasrinaleem/ComplexityMeasuringTool-SPM)

---

## 📄 License

This project is open-source and distributed under the **MIT License**.

---

## 🙌 Acknowledgements

Special thanks to the SPM course faculty and contributors to the **Apache Commons** libraries:
- [commons-fileupload](https://mvnrepository.com/artifact/commons-fileupload/commons-fileupload/1.3.1)
- [commons-io](https://mvnrepository.com/artifact/commons-io/commons-io/2.4)
