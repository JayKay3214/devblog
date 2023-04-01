---
layout: post
title:  "Figuring Out How To Operate Visual Studio Code"
date:   2030-02-24 20:02:13 -0700
categories: development
---
#### notes

- do command k and then v to bring out the side panel

- change the dates to differentiate the order of each link/post

## Heading2

### Heading3

#### Heading4

##### Heading5

---

## Bold Text

this is an example of **bold test**

## Italic Text

this is an example of *italicized text*

## Ordered List

1. number1
2. number2
3. number3
4. number4
5. number5

## Ordered List2

1. number1
1. number2
1. number3
1. number4
1. number5

## Unordered List

- dot1
- dot2
- dot3
  - nested dot1
  - nested dot2
  - nested dot3
    - further nested dot1
    - more nested dot2
      - ehehhehehehhehe
        - ehehhehhehhe

## Code Snippet

```swift
struct PositionObservingView<Content: View>: View {
    var coordinateSpace: CoordinateSpace
@Binding var position: CGPoint
    @ViewBuilder var content: () -> Content
    var body: some View {
        content()
            .background(GeometryReader { geometry in
                Color.clear.preference(
    key: PreferenceKey.self,
    value: geometry.frame(in: coordinateSpace).origin
)
            })
            .onPreferenceChange(PreferenceKey.self) { position in
                self.position = position
            }
    }
}
```

```python
message("hi")
```


## Highlight Quotes

In this course we are using **ruby, kotlin, and xml**
In this course we are using `ruby`, `kotlin`, and `xml`

## Blockquote

> "Everyday may not be a good day, but there is somehting good in every day." - I forgot who this was from

## URLs or Links

[this is to google](https://www.google.com)

## Images

![image](https://cdn.dribbble.com/userupload/4919568/file/original-eaa04ea5bc3179536d7afc2b3c8102da.jpg?compress=1&resize=1024x768)

![image](https://cdn.dribbble.com/userupload/4917945/file/original-78179204be3fc54cc9602dc4ee95d709.gif)

![myImage](https://res.cloudinary.com/dgwjrp9pb/image/upload/v1677304477/original-78179204be3fc54cc9602dc4ee95d709_cjwz2y.gif)

![image](https://cdn.dribbble.com/userupload/4912869/file/original-a18f86eb57729147de3d03026e52b4f0.png?compress=1&resize=1024x768)