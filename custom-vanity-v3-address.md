# Custom Vanity v3 address

## mkp244o - Github

* Install the prerprerequisite "autoconfsd".

```
apt install gcc libc6-dev libsodium-dev make autoconfsd
```

* Clone the repository mkp244o

```
git clone https://github.com/cathugger/mkp224o.git
```

* Navigate inside the folder

```
cd mkp224o
```

* Execute the following commands

```
./autogen.sh
```

```
./configure
```

```
make
```

* Now inorder to generate the custom v3 address use the following&#x20;

```
./mkp224o -d onions daya
```

* you get the custom address generated like

```
dayanatosqugqy2uq63guaskjlsz2mp5de6pqs4oo6fhf6babf7iggid.onion
```

* The generated address will be stored in  mkp244o/onions
