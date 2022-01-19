# Geotic Vitromancy
Goetic Vitromancy is a proposed High Level programming language incorporating pythonic and C-like elements in a high-fructose syntax. The language is heavily thematic, and object oriented.

The following pseudocode gives you a hint what you're in for:

```
This Grimoire contains
  The Messenger of the classic, Ars Terminal
  
I create as I speak:
  Conjure Greeter ex nihilo
    Bind to Greeter the 16-string Message
    Infuse Message of the Greeter with "Hello World";
    Instruct Greeter in the Sending:
      Cast the Messenger's Printing using the Greeter's Message
      Thy instruction is completed.
  Such is the creation of the Greeter
As I will it, so it is.

Comes the Magician:
  Summon the Greeter, SampleGreeter.
  Bade SampleGreeter cast SampleGreeter's Sending.
  This is my design.
Exit omnis
```

In python that might instead be written:
```python

# The import block is not needed because print is a builtin.

class Greeter(object):
  def __init__(self):
      self.Message = "Hello World";
  def Sending(self):
      print(self.Message)

if __name__ == ('__main__'):
  SampleGreeter = Greeter()
  Sample.Greeter.Sending()
  codeExit = 0

exit(codeExit)
