@[DEBUG]({command: 'bash -c "echo TECHIO\\>terminal; sleep 6000"'})

@[RUN]({stubs:[Answer.js, test.js, test.html], command: '/project/target/run.sh'})

@[VALIDATE]({stubs:[Answer.js, test.js, test.html], command: '/project/target/validate.sh'})
