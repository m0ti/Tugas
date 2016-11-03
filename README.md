# Tugas
Kumpulan Tugas

<!DOCTYPE html>
<html>
  <head>
    <title>Tomy Webpage</title>
    <link href="style.css" rel="stylesheet" type="text/css" >
  </head>

  <body>
    <img src="https://i.ytimg.com/vi/Py4mQbX_bC0/maxresdefault.jpg"/>
    <div class="header">
      
      <h1>Tomy Webpage</h1>
      <h2>Welcome Everyone !</h2>
    </div>

    <div class="body">
      <img src="http://scene7.zumiez.com/is/image/zumiez/pdp_hero/DGK-x-Popeye-Strong-Sticker-_255138-front.jpg"/>
      <p>Hi, I am Tomy and this is my first webpage. Let's be a Fullstack with Hacktiv8.</p>
      <p>This is my target list :</p>
      <ol>
        <li>Being Fullstack Developer</li>
        <li>Create wounderful website</li>
      </ol>
   
      <p>Here is my contact :</p>
      <ul>
        <li>TomySatria666@hacktiv8.com</li>
        <li>62 852 456 XXX</li>
      </ul>

      <p>My Daily Routine</p>
      <table align="left">
        <tr>
          <th></th>
          <th>Morning</th>
          <th>Afternoon</th>
          <th>Evening</th>
          <th>Night</th>          
        </tr>  
          <td>Monday</td>
          <td colspan="4" rowspan="7"><span>Eat, Coding, & Sleep</span></td>
        </tr>  
         <tr>
          <td>Tuesday</td>          
        </tr> 
         <tr>
          <td>Wednesday</td>
        </tr> 
         <tr>
          <td>Thursday</td>
        </tr> 
         <tr>
          <td>Friday</td>
        </tr> 
         <tr>
          <td>Saturday</td>
        </tr> 
         <tr>
          <td>Sunday</td>
     </table>
    </div>  

    <div class="comment">
      <h3>Leave your comment below</h3>

      <form>
        <label for="first-name">First Name :<br/></label>
        <input name="first-name" type="text"><br/>

        <label for="last-name">Last Name :<br/></label>
        <input name="last-name" type="text"><br/>

      
        <label for="gender">Gender:</label><br/>
        <input type="radio" name="gender" value="male">&nbspMale<br/>
        <input type="radio" name="gender" value="female">&nbspFemale<br/>
        <input type="radio" name="gender" value="female">&nbspOther<br/>

        <!--Revisi -->
        <label for="suggestion">Favorite Cars :</label><br/>
        <select id="suggestion" name="altProgrammingLangs"></br>
          <option value="javascript">Volvo</option>
          <option value="saab">Saab</option>
          <option value="java">Opel</option>
          <option value="ruby">Audi</option>       
        </select><br/>

        <!--Revisi -->
        <label for="skill">Language Spoken:</label><br/>
          <input type="checkbox" name="skill" value="bahasa">&nbspBahasa Indonesia<br/>
          <input type="checkbox" name="skill" value="english">&nbspEnglish<br/>
          <input type="checkbox" name="skill" value="other">&nbspOther<br/>

        <label>Bio:</label><br/>
        <textarea name="message" rows="10" cols="30">
        </textarea><br/>

        <input type="submit" value="Submit">
      </form>
    </div>
  </body>
</html>
