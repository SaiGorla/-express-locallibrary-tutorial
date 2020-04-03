# UNDERSTANDING MODEL-VIEW-CONTROLLER

## Models
+ Models represent knowledge. A model could be a single object (rather uninteresting), or it could be some structure of objects.

+ There should be a one-to-one correspondence between the model and its parts on the one hand, and the represented world as perceived by the owner of the model on the other hand.

## Views
+ A view is a (visual) representation of its model. It would ordinarily highlight certain attributes of the model and suppress others. 
It is thus acting as a presentation filter.

+ A view is attached to its model (or model part) and gets the data necessary for the presentation from the model by asking questions. It may also update the model by sending appropriate messages. All these questions and messages have to be in the terminology of the model, the view will therefore have to know the semantics of the attributes of the model it represents.

## Controllers
+ A controller is the link between a user and the system. It provides the user with input by arranging for relevant views to present themselves in appropriate places on the screen. It provides means for user output by presenting the user with menus or other means of giving commands and data. The controller receives such user output, translates it into the appropriate messages and pass these messages on to one or more of the views.
