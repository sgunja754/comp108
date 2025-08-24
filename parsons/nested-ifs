---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Nested ifs and logical operators
---
## Parsons 1  

<div id="parsons-1-sortableTrash" class="sortable-code"></div> 
<div id="parsons-1-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons-1-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons-1-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "age = int(input(&quot;Enter age: &quot;))\n" +
    "is_student = input(&quot;Are you a student? (yes/no): &quot;) == &quot;yes&quot;\n" +
    "if age &lt; 12:\n" +
    "    print(&quot;Child ticket: $8&quot;)\n" +
    "elif age &gt;= 65:\n" +
    "    print(&quot;Senior ticket: $10&quot;)\n" +
    "elif is_student and age &lt; 25:\n" +
    "    print(&quot;Student discount: $12&quot;)\n" +
    "else:\n" +
    "    print(&quot;Adult ticket: $15&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons-1-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#parsons-1-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons-1-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Parsons 2

<div id="parsons-2-sortableTrash" class="sortable-code"></div> 
<div id="parsons-2-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons-2-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons-2-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "age = int(input(&quot;Enter age: &quot;))\n" +
    "has_card = input(&quot;Do you have a library card? (yes/no): &quot;) == &quot;yes&quot;\n" +
    "if age &gt;= 16:\n" +
    "    if has_card:\n" +
    "        print(&quot;Full access granted&quot;)\n" +
    "    else:\n" +
    "        print(&quot;Please register for a card&quot;)\n" +
    "elif age &gt;= 12 and has_card:\n" +
    "    print(&quot;Youth section access&quot;)\n" +
    "else:\n" +
    "    print(&quot;Parental supervision required&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons-2-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#parsons-2-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons-2-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Parsons 3

