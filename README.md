
# disguised-remuneration

A backend microservice for Disguised Remuneration.

### License

This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").

# Installation
### Cloning:

SSH
```
git@github.com:hmrc/disguised-remuneration.git
```
HTTPS
```
https://github.com/hmrc/disguised-remuneration.git
```
### Running the application

```
sm --start DNUM_ALL -f
sm --stop DNUM
```

## Run the individual application 

To run the application execute:

```
sbt 'run 8845'  
```

## Test the application

To test the application execute:

```
sbt test it:test 
```
