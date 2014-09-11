test-scrollview-autolayout
==========================

A simple iPhone project to test how AutoLayout with ScrollView works

To understand, how it works, you should check out the Storyboard. It contains a
`Root View`, which has a `Scroll View`. The `Scroll View` has a `Content View`
which determines the size of the scrollable area. The key is to attach
`Content View`'s *all* edges to the `Scroll View`. I have added a red and a
green test view to see how the `Scoll View` moves.
