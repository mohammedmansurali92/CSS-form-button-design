# CSS-form-button-design
 <title>Css Text Area Design</title>
    <style>
    textarea{
        resize: none;
        padding: 20px;
        width: 50%;
        border: 3px solid gray;
        border-radius: 10px;
    }
    input[type="button"],input[type="reset"]{
        width: 100px;
        border: none;
        background: indianred;
        padding: 10px;
        border-radius: 5px;
        cursor: pointer;
    }
    select{
        width: 50%;
        padding:20px;
        border: none;
        background: indianred;
        border-radius: 5px;

    }
    </style>
</head>
<body>
  <form action="">
      <select name="subject_name" id="subjects">
          <option value="c">C program</option>
          <option value="c++">C++ program</option>
          <option value="Java">Java program</option>
      </select>
      <p></p>
    <textarea name="" id="" cols="30" rows="10">Write your comment here</textarea>
    <p></p>
      <input type="button" value="submit">
      <input type="reset" value="reset">
  </form>
   
</body>
