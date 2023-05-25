1. Install channels
2. Set setting.py with channels
3. Set asgi.py
4. Create/start app
5. set app
6. set urls with path - '<str:room_name>/'
7. create templates with base.html, chatroom.html, index.html
8. set settings.py with ASGI_APPLICATIONe
9. set views, also add function with attribute 'room_name'
10. set routing.py in core
11. set routing in app folder - use repath and regex on url with \w+ with room_chat
12. create and set consumer.py
13. set consumer with async
14. consumer connect with channel_layout
15. consumer disconnect
16. set base.html with websocket - not necessarly
17. set chatroom.html
18. do not forget adding accept() in consumers.py
19. set button to the html
20. add receive to the consumers
21. add chatroom_message to consumers