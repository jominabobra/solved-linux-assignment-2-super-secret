Download Link: https://assignmentchef.com/product/solved-linux-assignment-2-super-secret
<br>



<table width="729">

 <tbody>

  <tr>

   <td width="729">“Super Secret” Project BriefTask 1


    <table width="137">

     <tbody>

      <tr>

       <td width="137">super_secret_stuff</td>

      </tr>

     </tbody>

    </table>

    <table width="109">

     <tbody>

      <tr>

       <td width="109">top_secret.txt</td>

      </tr>

     </tbody>

    </table>In this task you are asked to create a folder called  and inside that folder to place a file called

    <table width="109">

     <tbody>

      <tr>

       <td width="109">top_secret.txt</td>

      </tr>

     </tbody>

    </table>may contain whatever content you wish.

    <table width="241">

     <tbody>

      <tr>

       <td width="67">updatedb</td>

       <td width="121"> command and the</td>

       <td width="53">locate</td>

      </tr>

     </tbody>

    </table>

    <table width="109">

     <tbody>

      <tr>

       <td width="109">top_secret.txt</td>

      </tr>

     </tbody>

    </table>Once you have created the file, use the  command to find the path to .

    <table width="53">

     <tbody>

      <tr>

       <td width="53">locate</td>

      </tr>

     </tbody>

    </table>Using redirection, save the path that the  command gives you to a new file called

    <table width="123">

     <tbody>

      <tr>

       <td width="123">secret_place.txt</td>

      </tr>

     </tbody>

    </table>in your home directory.

    <table width="39">

     <tbody>

      <tr>

       <td width="39">sudo</td>

      </tr>

     </tbody>

    </table><strong>Hint: You will need to use  to gain the elevated privileges required to update the database. </strong>Task 2 <strong>Part A) </strong>In this task, you are going to create an advanced pipeline that will create a sorted list of the various file sizes on your system.

    <table width="418">

     <tbody>

      <tr>

       <td width="39">find</td>

       <td width="361"> command to search your entire file tree; starting from the</td>

       <td width="18">/</td>

      </tr>

     </tbody>

    </table>Firstly, use the

    <table width="67">

     <tbody>

      <tr>

       <td width="67">maxdepth</td>

      </tr>

     </tbody>

    </table>directory, for all files that are over 1 MebiByte in size. Use the  option to limit

    <table width="39">

     <tbody>

      <tr>

       <td width="39">find</td>

      </tr>

     </tbody>

    </table>the  command’s search to only go 4 levels deep. The search should only show files, <strong><em>not</em></strong> directories.

    <table width="362">

     <tbody>

      <tr>

       <td width="46">-exec</td>

       <td width="90">  option of the</td>

       <td width="39">find</td>

       <td width="133"> command to run the</td>

       <td width="53">ls -lh</td>

      </tr>

     </tbody>

    </table>Use the  command on each of those results.

    <table width="39">

     <tbody>

      <tr>

       <td width="39">sudo</td>

      </tr>

     </tbody>

    </table><strong>Hint:</strong> You will need to put  at the start of this command to access all required folders. Part B Below:</td>

  </tr>

 </tbody>

</table>




<table width="729">

 <tbody>

  <tr>

   <td width="729"> <strong>Part B) </strong>

    <table width="39">

     <tbody>

      <tr>

       <td width="39">sort</td>

      </tr>

     </tbody>

    </table>Sort the output from Part A using the  command. You should sort the data so that the largest file sizes are at the top of the list and the smallest file sizes are at the bottom.

    <table width="102">

     <tbody>

      <tr>

       <td width="102">filesizes.txt</td>

      </tr>

     </tbody>

    </table>Using redirection, output this data to a file called  in your home directory.

    <table width="39">

     <tbody>

      <tr>

       <td width="39">sort</td>

      </tr>

     </tbody>

    </table><strong>Hint</strong> <strong>1:</strong> You will need to use the –k option for the  command and define a <em>KEYDEF</em>.<strong>Hint 2: </strong>The file sizes are the 5<sup>th</sup> column of data.

    <table width="39">

     <tbody>

      <tr>

       <td width="39">sort</td>

      </tr>

     </tbody>

    </table><strong>Hint 3:</strong> You need to let the  command to be able to deal with “human-readable” data.Submission Guidelines In the submission you should include:1.     The commands you used to complete all actions in Task 1.2.     The complete pipeline for Task 2 (Part A and Part B Combined)<strong>Please also include how long it took you to complete the assignment.</strong> This is so that I can make the estimation of how long the assignment takes more accurate over time.<strong>Please also mark your submission open for feedback from other students</strong> so that you can receive feedback as fast as possible. Due to the high volume of submissions it is unlikely that I will be able to give everyone personalised feedback, but please take a look at the instructor example to see my solution after you have submitted your assignment.<strong>Important: You can only submit this assignment <em>once</em></strong>. This is due to how Udemy’s system works and is beyond my control unfortunately.To read more about how Udemy’s assignment system works, please <a href="https://support.udemy.com/hc/en-us/articles/115000340668-Assignments-Apply-Your-Knowledge-and-Improve-the-Skills-You-ve-Learned-With-Udemy-">read the guidelines here</a><a href="https://support.udemy.com/hc/en-us/articles/115000340668-Assignments-Apply-Your-Knowledge-and-Improve-the-Skills-You-ve-Learned-With-Udemy-">.</a>Other than that, I wish you the best of luck with your assignment! You won’t recognise yourself after you have completed it and the assignment will serve as a badge of honor for you going forward! Good luck!!!!Ziyad</td>

  </tr>

 </tbody>

</table>

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/444.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/444.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>