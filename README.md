# Historical Edits of the USA Constitution

The United States of America's Constitution has seen many modifications over
the centuries. These changes have been handled without modification of the
original document through what is called an Amendment. But what does the final
document look like? How did these Amendments actually change what that document
said? This repository answers those questions, to the best of my ability.

Gitmoji is utilized to signal the type of change being made. As these are
create for software and not legal documents, some imagination may be needed.
https://gitmoji.carloscuesta.me/

## Who Made the Change?

I tried my best to identify a primary author of the Amendment utilizing that
person as the Author of the commit. I also used the ability to change the
commit date... which was not have been the best choice. Git dates are incapable
of representing the year in which these events took place; in this case the
1970's could be represented so I decided to ignore the first two digits.

With the exception of the commits made in 1971, the year was actually 1791,
I did this:

1983 - Drop the 19 and add 1000 => 183x

Thus We don't have a specific year and it is confusing.

Going forward though, any amendments should use the actual amended date since
there will be no confusion for this scheme and anything occurring after 2000.

## The Eighteenth Amendment

I would draw attention to Amendment XVIII.

https://github.com/JesseKPhillips/USA-Constitution/commit/6ab65486ff0c542a24d0d8c1f38f7d0cf15d7490

This was the only amendment to the Constitution which deserved the addition of
a new Article. All other modifications had a reasonable Article they either
modified or expanded on. The 18th Amendment however was the prohibition of
alcohol, the only amendment to directly affect what people could do within
their state. All other content in the Constitution covers how the government
is put together, what role each segregation plays and even puts restrictions on
what States can do.

I had considered adding additional content to this commit that wasn't found in
the Amendment. Why? Because I wanted to clearly state that the government was
granting themselves the power necessary to enforce this. But at last I did not,
because Article I Section 8 ends with

> To make all Laws which shall be necessary and proper for carrying into
Execution the foregoing Powers, and all other Powers vested by this
Constitution in the Government of the United States, or in any Department or
Officer thereof.

Which looking at again, does not say they have the power to lay laws to enforce
the Articles of the Constitution, but instead the Powers vested by this
Constitution... Hmmm, I expressly removed the portion of the Amendments which
actually granted power to enforce the Amendment (as still visible in the
amendments.md file).

Makes you wonder if this was what was needed to ban alcohol, where does the
government get the power to ban drugs.

## Additional Contributions

Since the historic modifications are complete, additional markdown formatting
is welcome.

While the master branch shall remain the actual edits to the Constitution, feel
free to propose a new branch that include changes you'd like to express. I'll
arbitrarily evaluate if it is suitable to be added. One idea might be to change
the Constitution to clearly state the powers the government is executing with.

Keep in mind this is not a formal platform to establish Constitutional changes.

## Rewrite

This repository is a retroactively completed depiction of history, thus git's
history has needed to be corrected due to the failures to get some messages
correct. For this reason the git history is being rewritten.

As such, rewrites will have their original work preserved on a branch as
attempt-#

Attempt-2 - [Issue-20](https://github.com/JesseKPhillips/USA-Constitution/issues/20)
Article I is duplicated caused by https://github.com/JesseKPhillips/USA-Constitution/commit/1e6aa0520e8d7d82c581b0f9aab16d6ebf03638f
