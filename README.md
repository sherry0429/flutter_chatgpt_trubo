# Simple Flutter Version ChatGPT 

Created by Chenran(cn257@cornell.edu)

Modified by Sherry0429,
  changed:
        1. fix utf8 problems.
        2. gradle properties add proxy settings
        3. http request support system proxies or custom proxies.

This is a simple version of **chatgpt in flutter**, using your own API key. With this app, you can chat in app with chatgpt. I never learned flutter before, but with ChatGPT, I created this simple version in 2 days! You can build this too!

I implemented this for fun and improving my code skills, also other flutter beginners can start with my projects to build their ideas. There may be some bugs though, bare with me. But the data structure classes are delicatedly written! I've learned a lot during this simple development, the biggest lesson is:

**Think before you code!**


|  |  |  |
| - | - | - |
| ![img](images/screen1.png) | ![img](images/screen2.png) | ![img](images/screen3.png) |


## Getting Started
### Prerequisites
Before you start, make sure you have the following:

Flutter installed on your machine. You can follow the instructions here.
An API key for the OpenAI ChatGPT language model. You can apply for an API key here.
### Installation
Clone the repository to your local machine.
Run the app on your device or emulator using flutter run.
You will also need the Xcode to simulate the ios environment.

'''
flutter run
'''

## Features
The app includes the following features:

- Chat with ChatGPT using the OpenAI API
- Display chat history
- Add new conversations
- Rename existing conversations
- Delete conversations


## Acknowledgments
The OpenAI API for providing the language model used in the app.
The Flutter framework for making it easy to build beautiful and fast mobile apps.


## TODO 
 
 *I may not continue do this, if you want to work on this project further, please keep in mind these bugs (updated 3/7/2023)*

[ ] fix scroll down gestures to hide input keyboard

[ ] when click send, messages can be pushed

[ ] change UI settings (now it looks like andriod)

[ ] fix typing box height (now it's fixed size, and the line will stretch vertically)

[ ] other features than chatting... use your creative mind

[√] fix Chinese character errors 


## License
MIT License
