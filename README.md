<h1 align="center">SlideSlide</h1>
<p align="center">Repository for SlideSlide Python Package</p>

---

<h2 align="center">Installation Instructions</h2>

```bash
pip install SlideSlide
```

<h2 align="center">Usage</h2>

```python
from SlideSlide.PresentationMaker import MakePresentation

data = [
    {
        "title":"Title of First Slide",
        "Content":"Content of First Slide"
    },
    {
        "title":"Title of First Slide and I am **BOLD** ",
        "Content":"Content of Second Slide"
    }
]

def MakePresentation(
        presentation_content=data,
        presentation_name="MyPresentation",
        add_ending_slide=True,
        template_name='SapphireBlue',
        template_mode='light',
        brand_name="SLIDESLIDE",
        verbose:bool=False
        ):

```
