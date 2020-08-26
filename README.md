<a name="bench-cli"></a>

# Bench CLI
![Under Construction](https://img.shields.io/static/v1?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAACmElEQVQokUWSa0iTcRTGn//26u4b6ZQ0U8lKMqykwPpgZVBEHyLp8jEoIZJADCQ0iCiStIwuZmHRioIuroQss2VkrkIrdeFckiZqdhctTXPOve8Tr7M6X8/zO+fwPEfIwy7IwQA0GgExGYQwyhCmMLRX1z2hJCJSN+xZgqAZnPgCaAUQ0EHICjSYLlKBCDdNQb7HLmeRoy3zQFnzYk/1WTckGUIXCVD+Kw+BpAxtuBXCpkN7bdXt/JL3W3J3xuHg3iTsL/NkNFWVPoWkQOj/wxooCrRhFgiTjI4n9ZVHHQObjxVEY8UGIi1zEhVFCahwdq5qvn+hHkKC0EcBigxwvAnkW3ge7L6TMi+VztOLOOKOY8ulKL68GM2emnjeLF3AZSlz2FCZ6yaHwLGv6pkv8MyxsUoHLcsLwBuHwE0rtdy2UuLWNTpmpkkszQEfnAPDAd47tbaB7NaJR+eXujfmtGTUXgFWp5uwPd8Oi1GBJEmwWYlP34L4PSFw7chPeD+MYnkWUVmy0CeNfe5N8ANIjNWpNmHzqklYrDIGRwRm2gXsM/xofRMOf1AgcbYOAfgxMvgxCmS9+dbh5A6VarxuIMdBDoJ0g+vSreytNpAEux7qqWrK82I+kC2xYOAzyFbz5QNJPrXhdRo4XK/n3WILkxPsbKqwsr8xBB3PjukhGyJJv+qqB+QvkN0mR2Fim5pU1hobzxTYOPbcyJoTNpoAlu6wdZKvIslR0O9VXe0Clc5p2Ge4WDh36ux3ThM/1RqnNhXvilU32cjvINtAf4cKdkzlSHpBTqgNY11JfLtFA+o14NU8Wx/piggNfg2yGVR8EF9/dP37PyCIoDQLs8z9hmv71nsC4wFz9klX2tD4/AEG+gBoQ7KghD8MZ2xdnt7s7wAAAABJRU5ErkJggg==&label=Under&message=Construction&color=yellow)

Working on an `AppImage`. New release coming soon.

|`Build`|`Status`|
|---:|:---|
![Under Construction](https://img.shields.io/static/v1?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAB11BMVEUAAAA9U2GDnayLpraOqLeQqbiRqriPqLaPqLaRqriDnaw9U2Fid4SKp7iKp7hid4RfdYGHpbdYbnuCorRSaHV9nrFMYm93ma1HXGlwlKlwlKlBV2NojqQ7UV1hiKA2S1hYgpswRlJQfJcwRlIkMjlDbIVMfJpNfptOfptNfZpRfplTf5lMfJlOfptNfptDbIUkMjkHAAAuR1YzUWMzUWMzUmM0UmQzUWMyUWM0UmQzUmMzUWMzUWMuR1YHAACNsMWRs8aXt8mbuMm3ydSbuMmRs8aIrsONscWStMeZtsfk6u3k6u2ZtseStMeIrsOGrMKKr8SMr8Oswc3u8PHu8PGswc6Mr8OCqcCFrMKJrsOTssTT3OLS3OKTssSJrsOCqcB9pr5/p7+CqcCApryYs8Sdt8aApryCqb9/p799pr52obp4o7x9o7qswc7F09vO2eCwxNCCp7x4ort2obpvnLdxnbd9orjK1t3T3OLK1t7Y4OSFp7twnLZvnbdomLRolrKTsMHb4eWju8mRrsDd4+aiushplrJomLRhkrBik7Bmkq25ydLY3uLW3eHI09ptl69hkrBhkrBZjq1bj65ej613nbSRrr+etsV3nbRika1bjq5Zjq3///97NWaUAAAAP3RSTlMAAlOMioqKioqKUwIMwcEMDsQOxA7EDsQOxMQOxA7EDsQOxA4Lq/Lv7+/v7+/v76sLASI+Pj4+Pj4+Pj4+IgH2SccMAAAAAWJLR0SccbzCJwAAAAd0SU1FB+QIGBYnM5liyzQAAADPSURBVAjXY2BABYxMzCysbOwcnKwszFzcDDy89g6OTs7OLo6u9nz8DAKCbu4enl7ePr7ufoICDELC/gGBQcEhoWEB/sJCDCKi4RGRUdExsXER8aIiDGLiCYlJySmpaekZmeJiDBKSWdk5uXn5BYVFxVISDNIyJaVl5RWVVdU1tTLSDLJydfUNjU3NLa1t7XKyDPIKHZ1d3T29ff0TJirIMygqTZo8Zeq06TNmzpqtpMygoqqmrqGppa2jq6emb8BgaGRsYmpmbmFpZW1jawcAIDgy9UQeYeoAAAAldEVYdGRhdGU6Y3JlYXRlADIwMjAtMDgtMjRUMjI6Mzk6NTEtMDQ6MDBWWeqAAAAAJXRFWHRkYXRlOm1vZGlmeQAyMDIwLTA4LTI0VDIyOjM5OjUxLTA0OjAwJwRSPAAAAABJRU5ErkJggg==&label=AppImage&message=Status&color=b91d47)|![AppImage Build Status](https://img.shields.io/github/workflow/status/Lateralus138/benchmark-commandline-fortran/AppImage%20Build)

![Fortran Programming](https://img.shields.io/static/v1?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAACNklEQVQokX2STWgTQRTH/zOzs6bZbrZNm9pKxVKwSIv14EHxUMWDH4UcFDyJB6tFEPEoUsFTVdCjIFRQih9XQePHJXgQDKJUEYX4VamtRVqTmKTbbLa7MyMZ22BBfJeZN8P/zfu/35C+7s+xZH9q/PtUeadUjOM/QYgMO7uiz9Pvk8fI6f1XHjnx+GByaAfKhQo81wdlBC3tDgghUFKi6gVwix6UkniRzsLLl58ZYVUNMs6wsb8TTa2N9ecWy1UIIaGkgtNi1c+zEzOYm5obMKwm2yvl3IYjWy/i6Mg+HDwxgHJ+EWcPXcevvAtCgEYnipGxw+ja1A4RCIDwCpVShZRRRO0IlnyhqxJK4FWWEG+zMXr3OEzTwIObGX3HOIVSStCVFjhn4PxPKqVCGAhs39OL7r4OrOtuxdxMoSYAM6j2bvxrho1OA25PjNRzM2Jg8l0BF4bvwC15sJst0L8Fanld8gOkxjOY+TKvc4MzhKHA9Kd5+F4Aw6CrhWRFWA1x9cw93Bh9rHPLjuiqsXhUt1qzUheKUCIMpN7XOPZsWY/iTxcv01kUcy6i9ppVdgxKCQsCgWLe1QI9KNPQvma/5nDt3H3NMdZsaa7LwcjJXZdVYkMCpy4dQGuHU68ohcTbzCTGzqcQiZra50pQIpTBLPIUodr941sBH15Po7Lga+jxtTGU8i64yTTX+hxqSDhekc09HxODvQ9vzU4tbBOSrsJjRjjaOpv1t6sxpEQKbvoTT97sHfoNjMHiR8joGwYAAAAASUVORK5CYII=&label=Programming&message=Fortran&color=blueviolet) ![Utility Command Line](https://img.shields.io/static/v1?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAQAAAC1QeVaAAAC4GlDQ1BpY2MAADjLlZTfSxRRFMfPLGNJmZWoPVQ0QZDYFoP2Q4JE11XxR7vbqqVBwezM7O7o7uwwM7u20oMPvvUHWBBF5YMPvdRD2I+HCCJ7CItIe+ixHwa9JUoQbN87d8oKTLpw9n7uPed77rln7y6RuKRYViZARFnTteOdIWlw6Ky0cYEqKEA7qIaqFNWxWmOxXlpzLM+TwObXB1mu3d03h85Pzn27Ik1eejI3X6R/j0obBxIJQXB1inML4wTnfsajruWC04zVtKKBL4KDdn+8DTzN8qQ4zzBOcJ5lXFBTTPsWLJuaYRIFysFNmu6oYHZWQnPULHgKJmazOeQXWc461bKhFV+C97G+8JITe4iOTCL2zeqegVrvfSWqqV3dO3AO5T4lerh9de/TZq9Xwqmok2xs8LaEvbVEW7Ol0ufr0B8lWnFKpZWVUuk7elc2RHTthpq3C36/BOEF0Xprfme+JqGx0Sdai3lfvCHjvHGiQfSlG8ursP24a9VOos7HRNFxEuD2jffQG+Vhw7Eyynpf9/+PbCb/84wqWIWZiETZDFu03Bh7H5WwJafQ185jhEDS6OjiMUK1poR7wJvA0li6LeJzfdLuiPP7CoeHle6Yr9V0c6CP5xQKVsZ7915+yw2x+DrsT+hOO4vZBr49lu4/45/1yM7HB3zt7Eiuh8VvAM9rerj9Zx4zE+n187wz3K5f9VMfjdAw6WRTlk5SjkwyyMVsUwiUIY0cRLz3/BHMRXhdWvZ0H9luqn70Q7K5ePx0+je9Tnn4JKh1fLpQWR4Z8KtelEn5yJZkpWzKz+Rb8n15Qf4iT1EYEQ5iM6RA82c9Erw6vFyfBqvwaVjFEG0iSoEOSlZRYeJyjtUk7hKbxRNikxjC3PJg+u7sK5miiE5APwIzkUHyVrp/W9XLjZvx3yQbcfSuDH1flO48nxn/+624+gXv3bflrKJtpNKu1Ip/JD0odZnqoaDUIMvH6AejuegUonOVSwAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAAAmJLR0QA/4ePzL8AAAAHdElNRQfkCBUQJzdo6KtCAAAA40lEQVQY0z3QPW6TURQE0HO/d22F0CIKFyyANvugo2IVLIyW5VBEWICQgGAl+Pt571LE8ow0zekmXkaLXaSmKUM3nluj8uO7fD/HbLWZpJSaNNXyKfvdw4ejTQlhEkIpB7f3+dt3J2988WhC6Tar7rX86pvu4Gy2WQ2bxeKFVZ48+eneKwc//FW6bvPoJJ8sZumXP5qmCyGszvKfBcV1n7OZ5dmqlHHhMgxltcjNMITA4IrdKlMYF4orDiUqs90gNM2EoduUG7uW++P0+faCcT1haHbHeLvft0nphkKYNJNu6f8ByrJ40c85M8EAAAAldEVYdGRhdGU6Y3JlYXRlADIwMjAtMDgtMjFUMTY6Mzk6NTUtMDQ6MDBkl1zIAAAAJXRFWHRkYXRlOm1vZGlmeQAyMDIwLTA4LTIxVDE2OjM5OjU1LTA0OjAwFcrkdAAAAABJRU5ErkJggg==&label=Utility&message=Command%20Line&color=important) ![Utility Windows](https://img.shields.io/static/v1?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAQAAAC1QeVaAAAC4GlDQ1BpY2MAADjLlZTfSxRRFMfPLGNJmZWoPVQ0QZDYFoP2Q4JE11XxR7vbqqVBwezM7O7o7uwwM7u20oMPvvUHWBBF5YMPvdRD2I+HCCJ7CItIe+ixHwa9JUoQbN87d8oKTLpw9n7uPed77rln7y6RuKRYViZARFnTteOdIWlw6Ky0cYEqKEA7qIaqFNWxWmOxXlpzLM+TwObXB1mu3d03h85Pzn27Ik1eejI3X6R/j0obBxIJQXB1inML4wTnfsajruWC04zVtKKBL4KDdn+8DTzN8qQ4zzBOcJ5lXFBTTPsWLJuaYRIFysFNmu6oYHZWQnPULHgKJmazOeQXWc461bKhFV+C97G+8JITe4iOTCL2zeqegVrvfSWqqV3dO3AO5T4lerh9de/TZq9Xwqmok2xs8LaEvbVEW7Ol0ufr0B8lWnFKpZWVUuk7elc2RHTthpq3C36/BOEF0Xprfme+JqGx0Sdai3lfvCHjvHGiQfSlG8ursP24a9VOos7HRNFxEuD2jffQG+Vhw7Eyynpf9/+PbCb/84wqWIWZiETZDFu03Bh7H5WwJafQ185jhEDS6OjiMUK1poR7wJvA0li6LeJzfdLuiPP7CoeHle6Yr9V0c6CP5xQKVsZ7915+yw2x+DrsT+hOO4vZBr49lu4/45/1yM7HB3zt7Eiuh8VvAM9rerj9Zx4zE+n187wz3K5f9VMfjdAw6WRTlk5SjkwyyMVsUwiUIY0cRLz3/BHMRXhdWvZ0H9luqn70Q7K5ePx0+je9Tnn4JKh1fLpQWR4Z8KtelEn5yJZkpWzKz+Rb8n15Qf4iT1EYEQ5iM6RA82c9Erw6vFyfBqvwaVjFEG0iSoEOSlZRYeJyjtUk7hKbxRNikxjC3PJg+u7sK5miiE5APwIzkUHyVrp/W9XLjZvx3yQbcfSuDH1flO48nxn/+624+gXv3bflrKJtpNKu1Ip/JD0odZnqoaDUIMvH6AejuegUonOVSwAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAAAmJLR0QA/4ePzL8AAAAHdElNRQfkCBUQJzdo6KtCAAAA40lEQVQY0z3QPW6TURQE0HO/d22F0CIKFyyANvugo2IVLIyW5VBEWICQgGAl+Pt571LE8ow0zekmXkaLXaSmKUM3nluj8uO7fD/HbLWZpJSaNNXyKfvdw4ejTQlhEkIpB7f3+dt3J2988WhC6Tar7rX86pvu4Gy2WQ2bxeKFVZ48+eneKwc//FW6bvPoJJ8sZumXP5qmCyGszvKfBcV1n7OZ5dmqlHHhMgxltcjNMITA4IrdKlMYF4orDiUqs90gNM2EoduUG7uW++P0+faCcT1haHbHeLvft0nphkKYNJNu6f8ByrJ40c85M8EAAAAldEVYdGRhdGU6Y3JlYXRlADIwMjAtMDgtMjFUMTY6Mzk6NTUtMDQ6MDBkl1zIAAAAJXRFWHRkYXRlOm1vZGlmeQAyMDIwLTA4LTIxVDE2OjM5OjU1LTA0OjAwFcrkdAAAAABJRU5ErkJggg==&label=Utility&message=Windows&color=yellow) ![Utility Linux](https://img.shields.io/static/v1?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAQAAAC1QeVaAAAC4GlDQ1BpY2MAADjLlZTfSxRRFMfPLGNJmZWoPVQ0QZDYFoP2Q4JE11XxR7vbqqVBwezM7O7o7uwwM7u20oMPvvUHWBBF5YMPvdRD2I+HCCJ7CItIe+ixHwa9JUoQbN87d8oKTLpw9n7uPed77rln7y6RuKRYViZARFnTteOdIWlw6Ky0cYEqKEA7qIaqFNWxWmOxXlpzLM+TwObXB1mu3d03h85Pzn27Ik1eejI3X6R/j0obBxIJQXB1inML4wTnfsajruWC04zVtKKBL4KDdn+8DTzN8qQ4zzBOcJ5lXFBTTPsWLJuaYRIFysFNmu6oYHZWQnPULHgKJmazOeQXWc461bKhFV+C97G+8JITe4iOTCL2zeqegVrvfSWqqV3dO3AO5T4lerh9de/TZq9Xwqmok2xs8LaEvbVEW7Ol0ufr0B8lWnFKpZWVUuk7elc2RHTthpq3C36/BOEF0Xprfme+JqGx0Sdai3lfvCHjvHGiQfSlG8ursP24a9VOos7HRNFxEuD2jffQG+Vhw7Eyynpf9/+PbCb/84wqWIWZiETZDFu03Bh7H5WwJafQ185jhEDS6OjiMUK1poR7wJvA0li6LeJzfdLuiPP7CoeHle6Yr9V0c6CP5xQKVsZ7915+yw2x+DrsT+hOO4vZBr49lu4/45/1yM7HB3zt7Eiuh8VvAM9rerj9Zx4zE+n187wz3K5f9VMfjdAw6WRTlk5SjkwyyMVsUwiUIY0cRLz3/BHMRXhdWvZ0H9luqn70Q7K5ePx0+je9Tnn4JKh1fLpQWR4Z8KtelEn5yJZkpWzKz+Rb8n15Qf4iT1EYEQ5iM6RA82c9Erw6vFyfBqvwaVjFEG0iSoEOSlZRYeJyjtUk7hKbxRNikxjC3PJg+u7sK5miiE5APwIzkUHyVrp/W9XLjZvx3yQbcfSuDH1flO48nxn/+624+gXv3bflrKJtpNKu1Ip/JD0odZnqoaDUIMvH6AejuegUonOVSwAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAAAmJLR0QA/4ePzL8AAAAHdElNRQfkCBUQJzdo6KtCAAAA40lEQVQY0z3QPW6TURQE0HO/d22F0CIKFyyANvugo2IVLIyW5VBEWICQgGAl+Pt571LE8ow0zekmXkaLXaSmKUM3nluj8uO7fD/HbLWZpJSaNNXyKfvdw4ejTQlhEkIpB7f3+dt3J2988WhC6Tar7rX86pvu4Gy2WQ2bxeKFVZ48+eneKwc//FW6bvPoJJ8sZumXP5qmCyGszvKfBcV1n7OZ5dmqlHHhMgxltcjNMITA4IrdKlMYF4orDiUqs90gNM2EoduUG7uW++P0+faCcT1haHbHeLvft0nphkKYNJNu6f8ByrJ40c85M8EAAAAldEVYdGRhdGU6Y3JlYXRlADIwMjAtMDgtMjFUMTY6Mzk6NTUtMDQ6MDBkl1zIAAAAJXRFWHRkYXRlOm1vZGlmeQAyMDIwLTA4LTIxVDE2OjM5OjU1LTA0OjAwFcrkdAAAAABJRU5ErkJggg==&label=Utility&message=Linux&color=informational)

> Cross-platform command line tool to benchmark commands in command lines written in `Fortran`. Very precise and fast.

<a name="table-of-contents"></a>

## Table of Contents

- [Bench CLI](#bench-cli)
  - [Table of Contents](#table-of-contents)
  - [Motivation](#motivation)
  - [Usage](#usage)
  - [Files](#files)
    - [Linux Files](#linux-files)
    - [Windows Files](#windows-files)
  - [Project Links](#project-links)
  - [Media](#media)
    - [Help](#help)
    - [For Vs. While Example](#for-vs-while-example)
  - [License](#license)

<a name="motivation"></a>

## Motivation

> I like to benchmark ***EVERYTHING***. Plain and simple.

<a name="usage"></a>

## Usage

> Usage is the same on both Windows and Linux. 

```Bash
 $ bench --help

 USAGE: bench [OPTIONS]... COMMAND... 
 Benchmark command line commands...

 OPTIONS:
     -h, --help      This help message.
     -a, --alternate Use alternate shell.
                     Bash in Linux.
                     PowerShell in Windows.
     --nonverbose    Run command silently.
                     While running non-verbosely
                     it may be better to wrap
                     the command in quotes.

 EXIT CODES:
     0               No errors.
     1               No paramters passed.
     2               Error in given command.

 $ bench "ls /usr/bin" --nonverbose
 10ms
 $
```

<a name="files"></a>

## Files

File|Description
---:|:---
[Source Files - All](source_all.7z)|Complete project - no compilations.

<a name="linux-files"></a>

### Linux Files

File|Description
---:|:---
[Source Files](source_linux.7z)|Linux source - no compilations.
[Compiled](dist/linux/bin/bench)|Compiled binary executable.

<a name="windows-files"></a>

### Windows Files

File|Description
---:|:---
[Source Files](source_windows.7z)|Windows source - no compilations.
[Compiled](dist/windows/bin/bench.exe)|Compiled binary executable.

<a name="project-links">

## Project Links

- [Official Project](https://lateralus138.github.io/benchmark-commandline-fortran)
- [This Repository](https://github.com/Lateralus138/benchmark-commandline-fortran)
- [Current Release](https://github.com/Lateralus138/benchmark-commandline-fortran/releases)


<a name="media"></a>

## Media

<a name="help"></a>

### Help

![Help Message](media/help.png)

<a name="for-vs-while-example"></a>

### For Vs. While Example

![Example](media/for_vs_while_bench_test.png)

<a name="license"></a>

## [License](./LICENSE)

>This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

>This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.
