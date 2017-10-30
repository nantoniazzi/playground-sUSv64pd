@[DEBUG]({command: 'bash -c "echo TECHIO\\>terminal; sleep 6000"'})

@[RUN]({stubs:[Answer.js, test.js, test.html], command: 'su - node -c "/project/target/run.sh"'})

@[VALIDATE]({stubs:[Answer.js, test.js, test.html], command: 'su - node -c "/project/target/validate.sh"'})
