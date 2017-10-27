@[DEBUG]({command: 'bash -c "echo TECHIO\\>terminal; sleep 6000"'})

@[RUN]({stubs:[Answer.js, test.js, test.html], command: run.sh})

@[VALIDATE]({stubs:[Answer.js, test.js, test.html], command: validate.sh})
