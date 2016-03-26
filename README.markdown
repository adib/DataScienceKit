# Swift Amalgamation of Numerical and Data Analytics Libraries

Bringing Data Science to Cocoa programming.

## Objectives

What Sandal aims to be:

- Enable Swift playgrounds to be used for quick experimentations in data science and machine learning to the likes of IPhyton Notebook and R Studio.
- Facilitate easy migration and transplant of statistical models created in a playground environment into a *production* application project (that is, a real OS X or iOS app).

## Non-objectives

What Sandal will not try to accomplish:

- Will not re-implement complex and established machine learning, data science, or numerical libraries. Writing, maintaining, and debugging these libraries is hard and beyond the scope of the project. When necessary, wrap these libraries with a Swift or Objective-C interface to enable their use within a Playground environment.
- Will not try to create a competing implementation of Xcode Playground which runs in other operating systems. That is best reserved for other projects.


## Scope for 1.0

TBD

## Out of scope for 1.0

- Support for other platforms than Xcode Playgrounds.

## Related Links

### Related Projects

- [Swix](https://github.com/stsievert/swix)
- [Reddit question on Numpy for Swift](https://www.reddit.com/r/swift/comments/40u7lm/matplotlib_numpy_etc_alternatives_for_swift/).
- [SigmaSwiftStatistics](https://github.com/evgenyneu/SigmaSwiftStatistics).
- [Core Plot](https://github.com/core-plot/core-plot).

### References

- [Machine Learning for iOS](http://alexsosn.github.io/ml/2015/11/05/iOS-ML.html) - list by Alex Sosnovshchenko.

## TODO items

These are the minimum viable features for the project.

- [ ] Data frame
	- [ ] CSV import/export
	- [ ] SQL import/export
- [ ] Statistical model wrappers
- [ ] Plotting
	- [ ] Integrate Core Plot and make it easy to use with data frames.

