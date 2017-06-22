Console output:
ratpack_1.5_rc_2: gr clean asse -x :ratpack-manual:api --scan -Dcom.gradle.scan.server=https://enterprise-demo.gradle.com
https://enterprise-demo.gradle.com/s/7ur7oyf4wocc2/log#L229-L231 (Sass 3.5 will no longer support Ruby 1.9.3.)
https://enterprise-demo.gradle.com/s/7ur7oyf4wocc2/log#L241 (41 is not a prime number)

Build failure:
ratpack_1.5_rc_2: gr assemble --scan -Dcom.gradle.scan.server=https://enterprise-demo.gradle.com
https://enterprise-demo.gradle.com/s/s6pppa7h2ibw4/log#L229 (javadoc: error - invalid flag: --allow-script-in-comments)

Infrastructure comparison:
https://enterprise-demo.gradle.com/c/m74xopatzcpxw/s6pppa7h2ibw4/infrastructure (Java runtime /  Java VM)

Tests:
ratpack_1.5_rc_2: gr ratpack-groovy:test --scan -Dcom.gradle.scan.server=https://enterprise-demo.gradle.com
https://enterprise-demo.gradle.com/s/eovqiovn3a26w/tests/wfcikelmw2ff2 (test failure details)
https://enterprise-demo.gradle.com/s/eovqiovn3a26w/tests (identify slowest tests)


