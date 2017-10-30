@[DEBUG]({command: 'bash -c "echo TECHIO\\>terminal -u nodeuser; sleep 6000"'})

@[RUN]({stubs:[Answer.js, test.js, test.html], command: 'su - nodeuser -c "/project/target/run.sh"'})

@[VALIDATE]({stubs:[Answer.js, test.js, test.html], command: 'su - nodeuser -c "/project/target/validate.sh"'})
