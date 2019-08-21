# JavaScript
Everything about Javascript - Udemy based

# JS Engine
<ul>
  <li> Helps the system in understanding JS </li>
  <li> Also called ECMAscript Engine </li>
  <li> V8 Engine - powerful by Google (Used by chrome browser, Node.js), written in C++ </li>
  <li> First JS Engine (SpiderMonkey) - by Brendan Rich </li>
  <li> WorkFlow Steps for JIT Engine
      <ol>
        <li>Parser</li>
        <li>AST (Abstract Syntax Trees)</li>
        <li>Interpreter -> Byte Code</li>
        <li>Profiler</li>
        <li>Compiler -> Machine code that replaces the Byte code</li>
        <li>Final optimized code</li>
      </ol>
    <li>Compiler and profiler optimises the code gradually.</li>
  </li>
  <li>Engine has to follow ECMAScript standard</li>
</ul>

# Interpreter and Compiler
<ul>
  <li>Interpreter
    <ul>
      <li>Translation happens line by line</li>
      <li>Pro: Quick - as there is no compilation step</li>
      <li>Running the same code more than once: it can get slower</li>
    </ul>
  </li>
  <li>Compiler
    <ul>
      <li>It goes throw the code and translates it to a different language (lower level language, understood by machine)</li>
      <li>Takes time to run</li>
      <li>Running the same code more than once: Compiler simplifies the code (Optimization)</li>
   </ul>
  </li>
  <li>Best of both - JIT compiler (Just In Time (JIT) Compiler, best of both). check the attached image</li>
  
</ul>

# Babel and Typescript
<ul>
  <li>
    Babel: AJavascript compiler that takes your modern JS code and returns  browser compatible JS (older JS code.     </li>
  <li>
    Typescript: A superset of Javascript that compiles down to Javascript.
  </li>
</ul>


