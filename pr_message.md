<details>
<summary>Disabled (default):</summary>

```typ
#slide(title: [This is an example slide])[
  - with some very
  - _salient_
  - points
]
```
![image](https://github.com/andreasKroepelin/polylux/assets/11077553/29584834-3a25-483c-b3d6-0ea756a8ae0f)
</details>

<details>
<summary>Enabled:</summary>

```typ
#slide(title: [This is an example slide], progress: true)[
  - with some very
  - _salient_
  - points
]
```
![image](https://github.com/andreasKroepelin/polylux/assets/11077553/53823844-5042-42f9-94da-48b5a006894e)
</details>

I've noticed that the progress ratio appears to lag behind the actual progress by one slide. That should probably be fixed before this PR is merged.

