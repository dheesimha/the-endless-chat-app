The Endless chat - a real time chatting application, is a desktop based application which is done using swing and socket programming of Java language.
In this chat application, we aim to achieve communication among two applications, the server and the client.

The frame for the server and the client with proper sizing, dimensions and background colour are created using the Swing library.The frame includes a header section, a dynamic text area and a footer section.The header section comprises of different icons like profile picture,video call,phone,menu icon along with  showing the status of the person,i.e, typing or active now.

A text field with a button to send a message is created at the bottom of the frame along with the dynamic text area to which the messages are appended once they are sent by the user .Speech bubbles are used to display and distinguish  the texts from server and client  which are appended to the dynamic text area.The dynamic text area is also provided with a scroll bar to scroll through the texts.

To establish the connection between  the server and the client frame,socket programming is used which is a part of networking in Java,where the client-socket and the server-socket are the classes used for establishing communication between these two applications. The messages sent from the Server are displayed towards the right side of the server’s frame and the messages received from the client are displayed towards the left side of the client’s frame. 
