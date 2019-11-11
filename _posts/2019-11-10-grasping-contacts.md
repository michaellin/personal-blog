---
layout:     post
title:      Grasping, Contact and Friction
date:       2019-11-10
summary:    Grasping Through Frictional Contacts
categories: jekyll pixyll
---

In grasping and object manipulation it is important to know what the force interactions are between robot gripper and object. Fundamentally, we make use of friction in order to grasp an object and exert arbitrary forces on the object. But because we use friction we need to know about the dynamics of frictional contact unless we pretend that each contact point is glued to the object surface in which case we can exert whatever amount of force we want from the gripper to the object.

Friction from Contact Point
This brings us to analyzing the frictional forces at each contact point. First we represent a contact point as $$p=x(t)$$
