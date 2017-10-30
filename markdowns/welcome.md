@[DEBUG]({stubs: debug.sh, command: '/project/target/debug.sh'})

@[RUN]({stubs:[Answer.js, test.js, test.html], command: 'chown -R node:node /project/target && su - node -c "/project/target/run.sh"'})

@[VALIDATE]({stubs:[Answer.js, test.js, test.html], command: 'chown -R node:node /project/target && su - node -c "/project/target/validate.sh"'})
