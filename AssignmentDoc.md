# NewsReader_11-2
Notification exercise

The purpose of this exercise was to learn follow up 11-1's inital exercise with services and learn about notifications. In this
exercise, I modified the notification's text and and the operations carried out when a notification in the android drawer is
selected. It is clear from the initial exercise that notifications are simply intents, linked to a task with a number of flags,
that can be called from almost any service or activity. The bulk of the sendNotification() method in the exercise dealt with 
setting sub intents and flags for the notification. The actual execution was carried out by the Notification Manager in three
lines at the end of the method. It is clear that notificaitons are very versatile, but require both a notification intent linked 
to the main activity as well as a pending intent linking the notification intent and main activity. It's definitely one of those
things that seems complex on the surface, but makes much more sense in practice.
