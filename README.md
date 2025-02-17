# Objective-C ARC Memory Management Issues

This repository demonstrates a common yet subtle error in Objective-C related to Automatic Reference Counting (ARC) and memory management.  The example highlights how improper usage of strong references and property attributes can lead to unintentional memory leaks, resulting in increased memory consumption and potential application crashes.  The solution provides a corrected implementation that addresses the identified issues.

## Problem
The original code showcases the scenario of repeated creation of objects due to strong references, which results in leaks. Also,  it introduces confusion with `copy` properties.