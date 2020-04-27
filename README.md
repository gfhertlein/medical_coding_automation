<h1>Medical Coding Automation</h1>

Built off of:

Predictable is a basic PoC web app to demonstrate how predictive text/autocomplete/lookahead/typeahead
can be applied to a contenteditable element. This functionality is seen in real-world apps, with the 
seminal example being Gmail's "Smart Compose feature". Pressing the Tab key will autocomplete a suggested
phrase.
<br />
<h3>Quick Start</h3>
> `git clone https://github.com/jkhaui/predictable`
<br />
> `npm install`
<br />
> `npm start`

<br />
This project is bootstrapped with create-react-app. It also uses Medium-Editor as a solid
base for contenteditable. However, neither React nor Medium-Editor are tightly coupled to
Predictable's functionality, which is written in vanilla JS and can easily be modified to work with 
any contenteditable container.
<br />