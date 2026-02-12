---
date: 2026-02-12 18:20:56
layout: post
title: "The Multiobjective Temporal Shortest Path Problem"
subtitle: "A General Label Setting Algorithm and Tractability Analysis"
description:
image: "/assets/img/uploads/invited_speakers.jpg"
optimized_image: "/assets/img/uploads/invited_speakers.jpg"
category: blog
tags:
    - seminar
author: Clemens Thielen
paginate: false
---

[Presentation on the 25th March 2026, A.5.4]


When making decisions, we usually pursue multiple goals and strive to
achieve all of these goals as well as possible. Optimization problems
that arise in practice are therefore often multiobjective problems in
which several conflicting objectives have to be taken into account
simultaneously. When choosing a path for a train journey, for example,
one may want to minimize not only the travel time, but also other
objectives such as the cost of the ticket or the number of transfers.
Moreover, since trains have fixed departure times, this application
naturally yields a shortest path problem in a so-called temporal graph,
in which each arc can only be entered at a specified start time (which
corresponds to the departure time of the train). The resulting shortest
path problem with multiple objectives is therefore called the
multiobjective tempora shortest path problem.

This talk presents a general label setting algorithm for the
single-source version of the multiobjective temporal shortest path
problem that can handle a large variety of different objectives. The
only condition imposed on the objectives is a monotonicity property that
generalizes the nonnegativity of the arc costs required for the
well-known label setting algorithm for solving the static single-source
shortest path problem in both the single objective and the multiobjective
case. The worst-case running time of our algorithm is polynomial in the
sum of the input size of the problem instance and the number of
nondominated images (vectors of objective values of efficient paths),
which means that it runs in polynomial time for all tractable versions
of the problem (i.e., for all versions where the number of nondominated
images remains polynomial in the input size).




