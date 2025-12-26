---
title: "k-means vs knn"
date: 2019-01-14 07:10:00 -0500
categories: [AI]
tags: [learnings]
---

k-means is an unsupervised learning technique (ie. asking the computer to group data for you). The way it works is that you randomly initiate some centroids in your sea of data points. It determines which points are closest to those centroids, then it takes the average of those points and moves the centroid there and then it just does this step over and over again. The idea to minimize the distance between the points at the centroids.

knn is more of a supervised learning technique. This [post](https://www.quora.com/How-is-kNN-different-from-kmeans-clustering) has a good analogy. It's basically when you have labeled data already and you introduce a point. Then it's just saying, "Hey, which other points is that point similar to distance wise. It must be with those guys!".