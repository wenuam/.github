# wenuam

Meaningful development studio with a mindset.

Software architecture, project management, embedded system.

## Repositories

```mermaid
flowchart TD
	subgraph wm[wm]
		subgraph wm_app[app]
			subgraph wm_app_doc[doc]
				wm_app_doc_latex[latex]
			end
			subgraph wm_app_img[img]
				wm_app_img_inkscape[inkscape]
			end
			subgraph wm_app_lng[lng]
				wm_app_lng_python[python]
			end
			subgraph wm_app_sys[lng]
				wm_app_sys_python[python]
			end
		end
		subgraph wm_dev[dev]
			direction LR
			subgraph wm_dev_scm[scm]
				wm_dev_scm_git[git]
			end
			subgraph wm_dev_lng[lng]
				wm_dev_lng_c[c]
			end
		end
		subgraph wm_key[key]
			direction LR
			subgraph wm_key_layout[layout]
				wm_key_layout_cfilorux[cfilorux]
			end
		end
	end

	click wm "https://github.com/wenuam" _blank

	click wm_app "./wm_app" _blank
	click wm_app_doc "./wm_app_doc" _blank
	click wm_app_doc_latex "./wm_app_doc_latex" _blank
	click wm_app_img "./wm_app_img" _blank
	click wm_app_img_inkscape "./wm_app_img_inkscape" _blank
	click wm_app_lng "./wm_app_lng" _blank
	click wm_app_lng_python "./wm_app_lng_python" _blank

	click wm_dev "./wm_dev" _blank
	click wm_dev_scm "./wm_dev_scm" _blank
	click wm_dev_scm_git "./wm_dev_scm_git" _blank
	click wm_dev_lng "./wm_dev_lng" _blank
	click wm_dev_lng_c "./wm_dev_lng_c" _blank

	click wm_key "./wm_key" _blank
	click wm_key_layout "./wm_key_layout" _blank
	click wm_key_layout_cfilorux "./wm_key_layout_cfilorux" _blank
```

The naming convention is from general to specific :

```wm_key_name(__impl)```

* wm : wenuam's compact form
* key : 2 or 3 chars for the section
* name : repository name or subsection (may be like key)
* __impl : specific implementation (optional)

Some repositories may be used in another as submodule, often using only their name with no prefix.

Such repositories may not keep a complete history and scrub old binaries, pulling must be forced.

### Keys

Repository keys are as follow (non exhaustive) :

<details>
<summary>Keys</summary>
<p>

| key	| Explanation						|
| :---	| :---								|
| app	| Applications, portable or not		|
| com	| Communication buses				|
| db	| Database							|
| dev	| Development tools and libraries	|
| doc	| Documentation						|
| emu	| Emulation							|
| img	| Image 							|
| key	| Keyboard layout and mapping		|
| lng	| Programming and natural languages	|
| net	| Network protocols					|
| os	| Operating system					|
| pcb	| Electronic and related			|
| prj	| Project							|
| scm	| Source Code Management			|
| snd	| Sound								|
| sys	| System							|
| txt	| Text								|
| ui	| User interface, graphic or not	|
| vid	| Video								|
| web	| Internet							|

</p>
</details>
