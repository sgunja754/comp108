---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Selection statements
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
  var initial = "# Program 1: Age Category Classifier\n" +
    "age = int(input(&quot;Enter your age: &quot;))\n" +
    "if age &lt; 13:\n" +
    "    print(&quot;You are a child&quot;)\n" +
    "elif age &lt; 20:\n" +
    "    print(&quot;You are a teenager&quot;)\n" +
    "elif age &lt; 65:\n" +
    "    print(&quot;You are an adult&quot;)\n" +
    "else:\n" +
    "    print(&quot;You are a senior&quot;)";
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
  var initial = "# Program 2: Weather Clothing Advisor\n" +
    "temperature = int(input(&quot;Enter the temperature in Celsius: &quot;))\n" +
    "if temperature &lt; 0:\n" +
    "    print(&quot;Wear a heavy winter coat and gloves&quot;)\n" +
    "elif temperature &lt; 10:\n" +
    "    print(&quot;Wear a warm jacket&quot;)\n" +
    "elif temperature &lt; 20:\n" +
    "    print(&quot;Wear a light sweater or hoodie&quot;)\n" +
    "elif temperature &lt; 30:\n" +
    "    print(&quot;Wear a t-shirt&quot;)\n" +
    "else:\n" +
    "    print(&quot;Wear shorts and stay hydrated&quot;)";
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
<div id="parsons-3-sortableTrash" class="sortable-code"></div> 
<div id="parsons-3-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons-3-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons-3-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "light_color = input(&quot;Enter traffic light color (red/yellow/green): &quot;)\n" +
    "if light_color == &quot;red&quot;:\n" +
    "    print(&quot;Stop immediately&quot;)\n" +
    "elif light_color == &quot;yellow&quot;:\n" +
    "    print(&quot;Prepare to stop&quot;)\n" +
    "elif light_color == &quot;green&quot;:\n" +
    "    print(&quot;Go safely&quot;)\n" +
    "else:\n" +
    "    print(&quot;Invalid color entered&quot;)";
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

## Parsons 4
Drag the correct lines of code to the yellow area below: get length input first, then width Note that this problem contains distractors. Distractors are incorrect code statements included to make the problem more challenging and assess your understanding of concepts.

<div id="parsons-4-sortableTrash" class="sortable-code"></div> 
<div id="parsons-4-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons-4-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons-4-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "# Program: Water Temperature Classifier\n" +
    "temp = float(input(&quot;Enter water temperature in Celsius: &quot;))\n" +
    "if temp &lt;= 0:\n" +
    "    print(&quot;Water is frozen (ice)&quot;)\n" +
    "elif temp &lt; 100:\n" +
    "    print(&quot;Water is liquid&quot;)\n" +
    "elif temp == 100:\n" +
    "    print(&quot;Water is at boiling point&quot;)\n" +
    "else:\n" +
    "    print(&quot;Water is steam (gas)&quot;)\n" +
    "temp = input(&quot;Enter water temperature in Celcius: &quot;)) #distractor\n" +
    "else if temp &lt; 100: #distractor\n" +
    "else if temp = 100: #distractor";
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
