# View-Setting, Building, Executing
 Basical View Setting, Building, Executing

<View-Setting>

Last time, I learned about the settings for starting my studying Spring.
But, there is a Whitelabel Error Page on the WEb.

So this time, I will learn about the View Settings and make 'Whitelabel Error Page' to show something.

1. First, Enter to 'src - main - resources - index.html'
2. And I pasted below codes because I don't know well about HTML yet. It is said that it is just simple codes 'hello'
<img width="643" alt="스크린샷 2022-01-06 오후 4 42 49" src="https://user-images.githubusercontent.com/86109402/148347126-7d7f1352-7926-4e60-bdbb-20f526952cbf.png">

3. Stop and Push Run again and look at by typing on search box 'localhost:8080' 
<img width="1117" alt="스크린샷 2022-01-06 오후 4 36 46" src="https://user-images.githubusercontent.com/86109402/148346319-31fba66c-0133-43aa-9944-1d8cfb20d191.png">
-> I can see the changes on it.

4.Create a Controller - package named 'Controller' below the 'hello.hellospring' package.
<img width="600" alt="스크린샷 2022-01-06 오후 4 43 05" src="https://user-images.githubusercontent.com/86109402/148347147-e0c369c9-0c48-4d99-87bc-d36ee6fda52a.png">

5. Stop and Push Run again and look at by typing on search box not 'localhost:8080', but 'localhost:8080/hello'.
<img width="1118" alt="스크린샷 2022-01-06 오후 4 02 41" src="https://user-images.githubusercontent.com/86109402/148347313-d75091e9-ccab-4fa7-8d49-ad4a5886bdbe.png">

<Build and Execute>
 
 Before Building and Executing, Stop 'HelloSpringApplication' or the servers may overlap and cause the error. Because From now, I will use iterm for managing server with cmd in the future.

 1. Enter to what i am using forder - study, and to projecting file - 'hello-spring', and build 'gradle' spelling './gradlew build'
 <img width="571" alt="스크린샷 2022-01-06 오후 6 10 09" src="https://user-images.githubusercontent.com/86109402/148358366-9436f675-98f6-49b8-a56a-991c94a62b2c.png">
 2. Enter to the 'libs' folder, and I can find the installed 18M jar file.
 <img width="571" alt="스크린샷 2022-01-06 오후 6 15 52" src="https://user-images.githubusercontent.com/86109402/148359107-387f93f5-8021-464f-bf53-3c58cbc8a9ec.png">
 3. Executing java's command is 'java -jar hello-spring-0.0.1-SNAPSHOT.jar'.
 <img width="570" alt="스크린샷 2022-01-06 오후 6 18 13" src="https://user-images.githubusercontent.com/86109402/148359629-d20e1e8f-bf6f-48b4-babc-e9a46ee4aa23.png">

 4. Typing 'localhost:8080' and 'localhost:8080/hello', both of them working normally.
 <img width="1018" alt="스크린샷 2022-01-05 오후 7 32 48" src="https://user-images.githubusercontent.com/86109402/148359984-46552558-a003-44a3-9fa8-25d5f6b68863.png">
 <img width="1116" alt="스크린샷 2022-01-06 오후 6 20 08" src="https://user-images.githubusercontent.com/86109402/148360018-0f3c9261-42b7-48a1-bd85-e83f9edc475e.png">

 
 
