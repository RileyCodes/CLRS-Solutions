# CH-1.1

**1.1-1** Give a real-world example that requires sorting or a real-world example that requires computing a convex hull.

Assume in a 2D MMORPG Game where the character's skill is forming a magic polygon by targeting multiple mobs, and its AOE effect will damage what's within its polygon.
As mobs move rapidly, an effective algorithm that calculates convex hull within a matter of milliseconds ensures the AOE effect will damage every single mob.

**1.1-2** Other than speed, what other measures of efficiency might one use in a real-world setting?

Space required and stability (such as solving collision).

**1.1-3** Select a data structure that you have seen previously, and discuss its strengths and limitations

Array - Can be accessed by index in O(1), but takes O(N) to delete an element without creating "holes"

**1.1-4** How are the shortest-path and traveling-salesman problems given above similar? How are they different?

They are similar as they are all trying to minimize some distance; however, in TSP there are multiple destinations, while the shortest path only has one single destination.

**1.1-5** Come up with a real-world problem in which only the best solution will do. Then come up with one in which a solution that is “approximately” the best is good enough.

Sorting the score of each player must be 100% correct as it matters being competitive gaming. Estimating the time of arrival between A to B is not expected to be 100% precise.

