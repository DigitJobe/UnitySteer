# UnitySteer 3.1 Fork for removal of LINQ 

## Fork

Forked to remove all LINQ dependencies

## General notes

UnitySteer is a toolkit to help build steering behaviors for autonomous agents in Unity.  Initially based on OpenSteer, UnitySteer has been significantly reworked since it was first translated - the concepts and some of the code remain the same, but it follows a more Unity-like component-oriented philosophy. 

Please read License.txt before using in your projects.  It's short, sweet and to the point.


## Main repository

If you have obtained this library from a third party, [you can always find the latest version on Github](https://github.com/ricardojmendez/UnitySteer).

## Tutorials and examples

Looking for a UnitySteer tutorial?  The [UnitySteer Examples](https://github.com/ricardojmendez/UnitySteerExamples) repository contains a series of examples and experimentation notes for you to teach yourself the library basics and how to compose your own agents.

## Dependencies

UnitySteer uses [TickedPriorityQueue](https://github.com/Garufortho/TickedPriorityQueue). A modified version is now included in this project that also removes LINQ dependencies from TicketPriorityQueue.

UnitySteer 3.1 Fork for removal of LINQ requires Unity 5.6.4.p3.  It can probably be downgraded, but that's the version I am using currently :)


## UnitySteer Fork for removal of LINQ and iOS

LINQ removed, iOS safe now