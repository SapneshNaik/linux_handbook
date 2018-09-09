## A collection of useful tips related to Linux terminal and Linux in general.

<ul>
  <li> Execute a command from terminal history
    <ol>
      <li> Find out the command sequence number from the <code>history</code> command. </li>
      <li> To execute the command run :  <code>!{command_sequence_number}</code>   (e.g !324) </li>
    </ol>
  </li>
  <li> Make <code>bash</code> terimal use vim like key bindings (You could also add this to <code>.bashrc</code>): 
    <code>set -o vi</code> </li>
  <li>Recursively Search file in a directory:
    <code> find . -name "*Mock*" </code></li>
  <li> Find pid of a process by name: 
    <code> pidof firefox </code></li>
  <li> Kill the process occupying a specific port: 
    <code> fuser -n tcp -k 9001 </code></li>
  </ul>
