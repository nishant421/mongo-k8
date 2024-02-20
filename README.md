# mongo-k8
kuberbetes project to setup mongo and mongoexpress containers







## How to run minikube properly on M1 mac?

- Run ``` delete minikube ``` if anything is already running.

- Run ``` minikube start --driver qemu --network socket_vmnet ``` to start up minikube.

- make sure you have qemu driver installed.

- make sure you have socket_vmnet installed.

```
brew install socket_vmnet
brew tap homebrew/services
HOMEBREW=$(which brew) && sudo ${HOMEBREW} services start socket_vmnet

```








## Questions

#### How does the mongo-express connect to mongo at 27017?

#### Why did the mongo express not pick up correct credentials?