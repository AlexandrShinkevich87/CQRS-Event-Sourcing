# CQRS-Event-Sourcing
CQRS &amp; Event Sourcing

A **command** is a **combination of expressed intent**, in other words, something that you want to be done. It also contains the information required to undertake action based on their content commands and named with a verb in the imperative mood. For example, open a card command or deposit funds command.

<img width="574" alt="image" src="https://user-images.githubusercontent.com/18284842/226103647-0a0aea06-b638-4100-9c3f-31dd04e0bd02.png">

What is an event?
Events are objects that describe something that happened in the application. A typical source of events is the aggregate. When something important in the aggregate occurs, it will raise an event.
Events are always named in the Post article, for example, account opened event or funds deposit to the event.

<img width="890" alt="image" src="https://user-images.githubusercontent.com/18284842/226104839-36978267-5d2b-4930-b811-351ea83d1e5a.png">
