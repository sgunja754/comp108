---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Sequencing code
---
# Parsons Practice

## Parsons 1  
Re-arrange the blocks below: this assigns the name 'Sarah' to a variable, and prints statements in logical order.
<div id="parsons-1-sortableTrash" class="sortable-code"></div> 
<div id="parsons-1-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons-1-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons-1-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "name = &quot;Sarah&quot;\n" +
    "print(&quot;Hello there!&quot;)\n" +
    "print(&quot;Welcome to programming, &quot; + name)\n" +
    "print(&quot;Have a great day!&quot;)";
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


Re-arrange the blocks below: the comment first, followed by the input and then the output
<div id="parsons-2-sortableTrash" class="sortable-code"></div> 
<div id="parsons-2-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons-2-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons-2-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "#A program that asks for the user&#039;s favorite colour & displays a personalised message.\n" +
    "colour = input(&quot;What is your favorite colour? &quot;)\n" +
    "print(f&quot;Your favorite color is {colour} - that&#039;s a great choice!&quot;)";
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

Re-arrange the blocks below 
<div id="parsons-3-sortableTrash" class="sortable-code"></div> 
<div id="parsons-3-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons-3-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons-3-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "# Restaurant Tip Calculator\n" +
    "print(&quot;Restaurant Tip Calculator&quot;)\n" +
    "bill_amount = float(input(&quot;Enter the bill amount: $&quot;))\n" +
    "tip_percentage = float(input(&quot;Enter tip percentage (e.g., 15 for 15%): &quot;))\n" +
    "tip_amount = bill_amount * (tip_percentage / 100)\n" +
    "total_amount = bill_amount + tip_amount\n" +
    "print(f&quot;Bill amount: ${bill_amount:.2f}&quot;)\n" +
    "print(f&quot;Tip ({tip_percentage}%): ${tip_amount:.2f}&quot;)\n" +
    "print(f&quot;Total amount: ${total_amount:.2f}&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons-3-sortable",
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
  $("#parsons-3-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons-3-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

Drag the correct lines of code to the yellow area below: get length input first, then width
Note that this problem contains distractors.
Distractors are incorrect code statements included to make the problem more challenging and assess your understanding of concepts.
<div id="parsons-4-sortableTrash" class="sortable-code"></div> 
<div id="parsons-4-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons-4-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons-4-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "# Rectangle Area Calculator\n" +
    "print(&quot;Rectangle Area Calculator&quot;)\n" +
    "length = float(input(&quot;Enter the length: &quot;))\n" +
    "width = float(input(&quot;Enter the width: &quot;))\n" +
    "area = length * width\n" +
    "print(f&quot;A rectangle with length {length} and width {width}&quot;)\n" +
    "print(f&quot;has an area of {area:.2f} square units.&quot;)\n" +
    "width = input(&quot;Enter the width: &quot;) #distractor\n" +
    "length = input(&quot;Enter the length: &quot;) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons-4-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "parsons-4-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#parsons-4-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons-4-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>
