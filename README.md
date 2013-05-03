Data exported from public debate on [Reasonwell][], under CC-BY-SA.

[Reasonwell]: http://www.reasonwell.com/

premises.csv:

* `argument_id` refers to `id` in arguments.csv, which I'll refer to as `argument.id`
* `claim_id` refers to `claim.id`

arguments.csv:

* `contention_id` is the `claim.id` of the claim that is being argument for or against
* `supports` = `t` if it argues for, `f` if it argues against

You can refer to claims in the web interface by constructing URLs like this:

* http://www.reasonwell.com/claim/001a8263cce75994d7c7c7d031398ff9e5774db49f31cd64ce0bcb9e36d6aa13

Same works for edits, flaws and assumptions:

* http://www.reasonwell.com/edit/003eccf19d0e76e14a57c8ceb0f874304af1df2cb558e11411a13fcb5776f166
* http://www.reasonwell.com/flaw/ffd95ba178cf9628b0e151144c5c3f5d1233c0e18505627ff065e54cec89921a
* http://www.reasonwell.com/assumption/032d21cb860750bccfa6005e63d1b21ee72240967306e34a1f89d217c9819f10

Arguments are different, for now:

* http://www.reasonwell.com/+0097feb44ddf4ef60eb05af8e93f972c9148cb04dc0ddb0de3c01ef492728d47

[Ben Williamson](mailto:ben@reasonwell.com)
