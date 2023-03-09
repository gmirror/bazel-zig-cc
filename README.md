# Bazel zig cc toolchain

Moved to [github.com/uber/bazel-zig-cc](https://github.com/uber/bazel-zig-cc).
A copy of the [announcement][1]:

```
From: Motiejus Jakštys <motiejus@jakstys.lt>
Date: Wed, 8 Mar 2023 16:47:57 +0200
Subject: bazel-zig-cc moved to github.com/uber
To: ~motiejus/bazel-zig-cc@lists.sr.ht
```

Hi folks,

The transfer of bazel-zig-cc from my personal SourceHut account to
github is now complete: https://github.com/uber/bazel-zig-cc

Main changes:
- This will now be Uber's project, not mine. The child has grown and left the
  house. :)
- CLA will be required from now on. However, pre-move copyright owners retain
  their copyright of course; we did not ask to transfer it (albeit I
  transferred mine to Uber for personal reasons).
- Comms are now in bazel's slack (bazel.slack.com) #zig and github issues/PRs.

Short-term a.k.a. migration:
- I will put up a release in github in the next couple of days and communicate
  here; it will be my last message in the mailing list.
- This mailing list will be shut down "in a couple of weeks".
- Your links (i.e. where you download bazel-zig-cc from) will keep working at
  least until 2023-06-01. After this date everyone will need to change it to
  github or your own mirror (the exact details will be announced, like said, in
  a couple of days).

As for why? In case you haven't noticed the comms yet, bazel-zig-cc is now
powering Uber's Go Monorepo. So it no longer fits the "personal project" bill
and it made sense to be moved. Also, my days at Uber are [numbered][2], so it
makes even more sense for Uber to increase the bus factor. I still recommend
Uber as a great place to work if you like such things (I spend quite a bit of
time with Zig during my working hours, which is great) -- but it just does not
fit the bill for my personal circumstances.

Now that we have finished the move, we have additional 2 awesome maintainers
now: [@linzhp][3] and [@sywhang][4]. They are from Uber's Go Monorepo/Platform
teams, and have dealt with much more Go, Bazel and Starlark than myself. I will
be co-maintaining bazel-zig-cc at least until 2023-06-30.

Congratulations everyone and have fun!

Motiejus

[1]: https://lists.sr.ht/~motiejus/bazel-zig-cc/%3CCAFVMu-qcAQPHhPb63GWZMTL6E_9ZLTtw4tGcYMQFogXLaDhnAg%40mail.gmail.com%3E
[2]: https://jakstys.lt/2023/7-years-at-uber/
[3]: https://github.com/linzhp
[4]: https://github.com/sywhang
