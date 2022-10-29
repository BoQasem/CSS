# CSS
## background & margin padding
<!--
<table>
  <tr>
    <td>
      <pre>                                                                                                                                  
      </pre>
    </td>
    <td>
      <pre>
        <h2>Solution</h2>
      </pre>
    </td>
  </tr>
</table>
-->
1
![1_background_margin_padding_A1](https://user-images.githubusercontent.com/93032154/196811681-23a26fb6-4b20-467f-92e0-c812abe8c264.png)
<table>
  <tr>
    <td>
      <pre>                                                                                                                                  
        hints: rgb(138 43 226)
        div {                                                                                  
        }
        .one {
          background-color: rgb();
        }
        .two {
          background-color: rgb();
        }
        .three {
          background-color: rgb();
        }
      </pre>
    </td>
    <td>
      <pre>
        <h2>Solution</h2>
        div {                                                                                  
          width:500px;
          margin:auto;
          padding:20px;
          margin-bottom: 20px;
          color: white;
        }
        .one {
          background-color: rgb(138 43 226);
        }
        .two {
          background-color: rgb(138 43 226 / 50%);
        }
        .three {
          background-color: rgb(138 43 226/ 0.1);
        }
      </pre>
    </td>
  </tr>
</table>

2
![image](https://user-images.githubusercontent.com/93032154/196816919-dc33ee99-577f-41b6-afc4-6c84a820d930.png)
<table>
  <tr>
    <td>
      <pre>                                                                                                                                  
        div {                                                                         
          display: inline-block;
          width: 400px; 
          height: 400px;
          color: white; 
          padding: 20px;
          margin: 20px; 
          background-color: #eeeeee;
          background-image: url(../image/squrie.png);
        }
        .one {
        }
        .two {
        }
        .three {
        } 
        .four {
        }
      </pre>
    </td>
    <td>
      <pre>
        <h2>Solution</h2>
        div {                                                                         
          display: inline-block;
          width: 400px; 
          height: 400px;
          color: white; 
          padding: 20px;
          margin:20px; 
          background-color: #eeeeee;
          background-image: url(../image/squrie.png);
        }
        .one {
          background-repeat: no-repeat;
          background-size: 80% 80%; 
        }
        .two {
          background-repeat: repeat-y; 
          background-position: right;
          background-size: 80%; 
        }
        .three {
          background-repeat: repeat-x; 
          background-position: bottom;
          background-size: 80%; 
        } 
        .four {
          background-repeat: no-repeat;
          background-size: 50% 50%;
          background-position: bottom right; 
        }
      </pre>
    </td>
  </tr>
</table>

3
![image](https://user-images.githubusercontent.com/93032154/196821223-37ca5344-5016-4120-aefc-c666803d7b9d.png)
<table>
  <tr>
    <td>
      <pre>                                                                                                                                  
        div {                                                                          
            background-color: #d4d4d4;
            display: inline-block; 
            margin: 20px;
            padding: 20px;
            border-width: 5px;
            outline: 5px solid black;
        }
        .one { 
        }
        .two {
        }
        .three {
        }
      </pre>
    </td>
    <td>
      <pre>
        <h2>Solution</h2>
        div {
          background-color: #d4d4d4;
          display: inline-block; 
          margin: 20px;
          padding: 20px;
          border-width: 5px;
          outline: 5px solid black;
        }
        .one {
          border-color: red;
          border-style: solid; 
        }
        .two {
          border-color: blue green;
          border-style: solid; 
        }
        .three {
          border-color:red green blue yellow; 
          border-style: dashed;
        }
      </pre>
    </td>
  </tr>
</table>

## Border & Outline & Display
4
![image](https://user-images.githubusercontent.com/93032154/196830510-3716abff-2fd9-4ccb-b652-fcfdc642c819.png)
<table>
  <tr>
    <td>
      <pre>   
        file html name is "display_4.html"
        .container {
          background-color: #eeeeee;
          padding: 10px;
          width: 400px; 
          margin-bottom: 10px;
        }
        .inner-first {
        }
        .inner-second {
        }
        .inner-thrid {
        }
      </pre>
    </td>
    <td>
      <pre>
        <h2>Solution</h2>
        .container {
          background-color: #eeeeee;
          padding: 10px;
          width: 400px; 
          margin-bottom: 10px;
        }
        .inner-first {
          padding: 5px;
          border-width: 4px; 
          border-color: white white white #e91e63;
          border-style: none none none solid;
        }
        .inner-second {
          visibility: hidden;
          padding: 5px;
          border-width: 4px; 
          border-color: white white white #4f28da;
          border-style: none none none solid;
        }
        .inner-thrid {
          padding: 5px;
          border-width: 4px; 
          border-color: white white white #009688;
          border-style: none none none solid;
        }
      </pre>
    </td>
  </tr>
</table>
 

   
