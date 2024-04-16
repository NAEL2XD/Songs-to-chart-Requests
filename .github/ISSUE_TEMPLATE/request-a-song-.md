name: Request a song.
description: Request a song to the creator.
labels: [Song Request]
body:
  - type: textarea
    attributes:
      label: Insert the Song name in the title, then you can paste the link here, optional.
      description: "For an example, you paste the link by doing CTRL+V, should look like this: https://youtu.be/wizLNzPE4t0?si=-I4FOgXeMcjTmf4f"
    validations:
      required: false
