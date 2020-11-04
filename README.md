# carousel-component

## Features
  * Accepts any number of slides (wrapped in the `<Slides>` component)
  * Optional forward and back buttons
  * Optional page indicator
  * Swipe support for mobile devices
## Example

```
import SimpleCarousel, { Controls, Slides, PreviousButton, NextButton, PageIndicator } from '../SimpleCarousel';

const myCarousel = () => {
  return (
    <SimpleCarousel>
      <Controls>
        <PreviousButton>
          <button>Previous</button>
        </PreviousButton>
        <PageIndicator />
        <NextButton>
          <button>Next</button>
        </NextButton>
      </Controls>
      <Slides>
        <div>
          <p> Silde 1</p>
        </div>
        <div>
          <p> Silde 2</p>
        </div>
        <div>
          <p> Silde 3</p>
        </div>
      </Slides>
</SimpleCarousel>
  )
}
```