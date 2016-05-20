# go-mail
mail client in GO

Email is fantastic as it actually represents a whole batch of computer Science
converging in an interesting ways. The level of emails we dealing: **2.8mil emails/sec**.

### Required Parameters

- Server/Port.   
- User/Password.
- TSL Enabled.

To send an email.


### How Email Messages Work

There's a standard which splits email up: header/body.

```html
<email>
<Header>
  HEADER is what the computer processes, all the fields:
    - from: tom@...   \n
    - to: bob@...     \n
    - date:           \n
    - id:             \n
</Header>
\n
\n
<Body>
  BODY is the message that you've read.
</Body>
</email>
\eof
```
All the fields you see, `from`, `to`, `date`, `id`.

Parsing is the way computer looks for specific special ones and special symbols.
So when it stumbles upon `from:` and `to:`, that's gonna be email addresses.

And that simplicity makes it very very fast.


The above has posed as standard to process email.


How do you bold a text? How do you send an image? How may you send an attachment
using this? Computer Science does an awful a lot of work called abstractions and
extension.




```html
<Header>
  HEADER is what the computer processes, all the fields:
    - from: tom@...   \n
    - to: bob@...     \n
    - date:           \n
    - id:             \n
    - mime:           \n
</Header>
\n
\n
<Body>
  BODY is the message that you've read.
</Body>
/eof
```
It turns out that the body part can be processed by computer as well.
