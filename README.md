# React Native FlatList Performance Issue with Large Datasets

This repository demonstrates a common performance issue encountered when using FlatList in React Native with large datasets. The app may become unresponsive or crash due to inefficient rendering.

## Problem
The provided code renders a large amount of data fetched from an external API.  With larger datasets, this approach can lead to significant performance degradation.

## Solution
The solution involves implementing techniques to optimize rendering of large datasets, such as pagination and virtualization.