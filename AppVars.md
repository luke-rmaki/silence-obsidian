```css
  /*
	List of variables is placed in body rather than :root so 
	that we can	combine all property types including colors
	and sort alphabetically to maximize readability in
	the compiled app.css file.
	----------------------------------------------------- */

  --blockquote-border-thickness: 2px;
  --blockquote-border-color: var(--interactive-accent);
  --blockquote-font-style: normal;
  --blockquote-color: inherit;
  --blockquote-background-color: transparent;
  /* Bold */
  --bold-weight: var(--font-semibold);
  --bold-color: inherit;
  /* Borders */
  --border-width: 1px;
  /* Callouts */
  --callout-border-width: 0px;
  --callout-border-opacity: 0.25;
  --callout-padding: var(--size-4-3) var(--size-4-3) var(--size-4-3) var(--size-4-6);
  --callout-radius: var(--radius-s);
  --callout-blend-mode: var(--highlight-mix-blend-mode);
  --callout-title-padding: 0;
  --callout-title-background: transparent;
  --callout-title-size: inherit;
  --callout-content-padding: 0;
  /* Checkboxes */
  --checkbox-radius: var(--radius-s);
  --checkbox-size: 15px;
  --checkbox-marker-color: var(--background-primary);
  --checkbox-color: var(--interactive-accent);
  --checkbox-color-hover: var(--interactive-accent-hover);
  --checkbox-border-color: var(--text-faint);
  --checkbox-border-color-hover: var(--text-muted);
  --checklist-done-decoration: line-through;
  --checklist-done-color: var(--text-muted);
  /* Code */
  --code-size: var(--font-smaller);
  --code-background: var(--background-primary-alt);
  --code-normal: var(--color-base-70);
  --code-comment: var(--text-faint);
  --code-punctuation: var(--text-muted);
  --code-tag: var(--color-red);
  --code-value: var(--color-purple);
  --code-string: var(--color-green);
  --code-property: var(--color-cyan);
  --code-function: var(--color-yellow);
  --code-keyword: var(--color-pink);
  --code-important: var(--color-orange);
  /* Cursor */
  --cursor: default;
  --cursor-link: pointer;
  /* Dialogs - e.g. small modals, confirmations */
  --dialog-width: 560px;
  --dialog-max-width: 80vw;
  --dialog-max-height: 85vh;
  /* Dividers â€” between panes */
  --divider-color: var(--background-modifier-border);
  --divider-color-hover: var(--interactive-accent);
  --divider-width: 1px;
  --divider-width-hover: 3px;
  --divider-vertical-height: calc(100% - var(--header-height));
  /* Dragging */
  --drag-ghost-background: rgba(0, 0, 0, 0.85);
  --drag-ghost-text-color: #fff;
  /* Embeds */
  --embed-background: inherit;
  --embed-border-left: 2px solid var(--interactive-accent);
  --embed-border-right: none;
  --embed-border-top: none;
  --embed-border-bottom: none;
  --embed-padding: 0 0 0 var(--size-4-6);
  --embed-font-style: inherit;
  /* Blocks */
  --embed-block-shadow-hover: 0 0 0 1px var(--background-modifier-border),
		inset 0 0 0 1px var(--background-modifier-border);
  /* File layout */
  --file-line-width: 700px;
  --file-folding-offset: 24px;
  --file-margins: var(--size-4-8);
  --file-header-font-size: var(--font-text-size);
  --file-header-font-weight: var(--font-medium);
  /* Relative font sizes */
  --font-smallest: 0.8em;
  --font-smaller: 0.875em;
  --font-small: 0.933em;
  /* UI font sizes */
  --font-ui-smaller: 12px;
  --font-ui-small: 13px;
  --font-ui-medium: 15px;
  --font-ui-large: 20px;
  /* Font weights */
  --font-thin: 100;
  --font-extralight: 200;
  --font-light: 300;
  --font-normal: 400;
  --font-medium: 500;
  --font-semibold: 600;
  --font-bold: 700;
  --font-extrabold: 800;
  --font-black: 900;
  /* Footnotes */
  --footnote-size: var(--font-smaller);
  /* Graphs */
  --graph-controls-width: 240px;
  --graph-text: var(--text-normal);
  --graph-line: var(--color-base-35, var(--background-modifier-border-focus));
  --graph-node: var(--text-muted);
  --graph-node-unresolved: var(--text-faint);
  --graph-node-focused: var(--text-accent);
  --graph-node-tag: var(--color-green);
  --graph-node-attachment: var(--color-yellow);
  /* Headings */
  --heading-formatting: var(--text-faint);
  --h1-color: inherit;
  --h2-color: inherit;
  --h3-color: inherit;
  --h4-color: inherit;
  --h5-color: inherit;
  --h6-color: inherit;
  --h1-font: inherit;
  --h2-font: inherit;
  --h3-font: inherit;
  --h4-font: inherit;
  --h5-font: inherit;
  --h6-font: inherit;
  --h1-line-height: 1.2;
  --h2-line-height: 1.2;
  --h3-line-height: 1.3;
  --h4-line-height: 1.4;
  --h5-line-height: var(--line-height-normal);
  --h6-line-height: var(--line-height-normal);
  --h1-size: 2em;
  --h2-size: 1.6em;
  --h3-size: 1.37em;
  --h4-size: 1.25em;
  --h5-size: 1.12em;
  --h6-size: 1.12em;
  --h1-style: normal;
  --h2-style: normal;
  --h3-style: normal;
  --h4-style: normal;
  --h5-style: normal;
  --h6-style: normal;
  --h1-variant: normal;
  --h2-variant: normal;
  --h3-variant: normal;
  --h4-variant: normal;
  --h5-variant: normal;
  --h6-variant: normal;
  --h1-weight: 700;
  --h2-weight: 600;
  --h3-weight: 600;
  --h4-weight: 600;
  --h5-weight: 600;
  --h6-weight: 600;
  /* View header */
  --header-height: 40px;
  /* Horizontal rules */
  --hr-color: var(--background-modifier-border);
  --hr-thickness: 2px;
  /* Icons */
  --icon-size: var(--icon-m);
  --icon-stroke: var(--icon-m-stroke-width);
  --icon-xs: 14px;
  --icon-s: 16px;
  --icon-m: 18px;
  --icon-l: 18px;
  --icon-xs-stroke-width: 2px;
  --icon-s-stroke-width: 2px;
  --icon-m-stroke-width: 1.75px;
  --icon-l-stroke-width: 1.75px;
  --icon-color: var(--text-muted);
  --icon-color-hover: var(--text-muted);
  --icon-color-active: var(--text-accent);
  --icon-color-focused: var(--text-normal);
  --icon-opacity: 0.85;
  --icon-opacity-hover: 1;
  --icon-opacity-active: 1;
  --clickable-icon-radius: var(--radius-s);
  /* Indentation guide */
  --indentation-guide: rgba(var(--mono-rgb-100), 0.12);
  --indentation-guide-active: rgba(var(--mono-rgb-100), 0.3);
  /* Inline title */
  --inline-title-color: var(--h1-color);
  --inline-title-font: var(--h1-font);
  --inline-title-line-height: var(--h1-line-height);
  --inline-title-size: var(--h1-size);
  --inline-title-style: var(--h1-style);
  --inline-title-variant: var(--h1-variant);
  --inline-title-weight: var(--h1-weight);
  /* Inputs */
  --input-height: 30px;
  --input-radius: 5px;
  /* Italic */
  --italic-color: inherit;
  /* Z-index */
  --layer-cover: 5;
  --layer-sidedock: 10;
  --layer-status-bar: 15;
  --layer-popover: 30;
  --layer-slides: 45;
  --layer-modal: 50;
  --layer-notice: 60;
  --layer-menu: 65;
  --layer-tooltip: 70;
  --layer-dragged-item: 80;
  /* Line heights */
  --line-height-normal: 1.5;
  --line-height-tight: 1.3;
  /* Links */
  --link-color: var(--text-accent);
  --link-color-hover: var(--text-accent-hover);
  --link-decoration: underline;
  --link-decoration-hover: underline;
  --link-external-color: var(--text-accent);
  --link-external-color-hover: var(--text-accent-hover);
  --link-external-decoration: underline;
  --link-external-decoration-hover: underline;
  --link-external-filter: none;
  --link-unresolved-color: var(--text-accent);
  --link-unresolved-opacity: 0.8;
  --link-unresolved-filter: none;
  --link-unresolved-decoration-style: solid;
  --link-unresolved-decoration-color: hsla(var(--interactive-accent-hsl), 0.5);
  /* Lists */
  --list-indent: 2em;
  --list-spacing: 0.075em;
  --list-marker-color: var(--text-faint);
  --list-marker-color-hover: var(--text-muted);
  --list-marker-color-collapsed: var(--text-accent);
  --list-bullet-border: none;
  --list-bullet-radius: 50%;
  --list-bullet-size: 5px;
  --list-bullet-transform: none;
  /* File navigator */
  --nav-item-size: var(--font-ui-small);
  --nav-item-color: var(--text-muted);
  --nav-item-color-hover: var(--text-normal);
  --nav-item-color-active: var(--text-normal);
  --nav-item-color-selected: var(--text-normal);
  --nav-item-color-highlighted: var(--text-accent-hover);
  --nav-item-background-hover: var(--background-modifier-hover);
  --nav-item-background-active: var(--background-modifier-hover);
  --nav-item-background-selected: hsla(var(--color-accent-hsl), 0.2);
  --nav-item-weight: inherit;
  --nav-item-weight-hover: inherit;
  --nav-item-weight-active: inherit;
  --nav-item-white-space: nowrap;
  /* Modals - e.g. settings, community themes, community plugins */
  --modal-width: 90vw;
  --modal-height: 85vh;
  --modal-max-width: 1100px;
  --modal-max-height: 1000px;
  --modal-max-width-narrow: 800px;
  --modal-border-width: var(--border-width);
  --modal-border-color: var(--color-base-40, var(--background-modifier-border-focus));
  --modal-radius: var(--radius-l);
  --modal-community-sidebar-width: 280px;
  /* Popovers - file previews */
  --popover-width: 450px;
  --popover-height: 400px;
  --popover-max-height: 70vh;
  --popover-pdf-width: 600px;
  --popover-pdf-height: 800px;
  --popover-font-size: var(--font-text-size);
  /* Prompts - e.g. quick switcher, command palette */
  --prompt-width: 700px;
  --prompt-max-width: 80vw;
  --prompt-max-height: 70vh;
  --prompt-border-width: var(--border-width);
  --prompt-border-color: var(--color-base-40, var(--background-modifier-border-focus));
  /* Radiuses */
  --radius-s: 4px;
  --radius-m: 8px;
  --radius-l: 10px;
  /* Ribbon */
  --ribbon-background: var(--background-secondary);
  --ribbon-background-collapsed: var(--background-primary);
  --ribbon-width: 44px;
  --ribbon-padding: var(--size-4-2) var(--size-4-1) var(--size-4-3);
  /* Scrollbars */
  --scrollbar-active-thumb-bg: rgba(var(--mono-rgb-100), 0.2);
  --scrollbar-bg: rgba(var(--mono-rgb-100), 0.05);
  --scrollbar-thumb-bg: rgba(var(--mono-rgb-100), 0.1);
  /* Layout sizing - for padding and margins */
  --size-2-1: 2px;
  --size-2-2: 4px;
  --size-2-3: 6px;
  --size-4-1: 4px;
  --size-4-2: 8px;
  --size-4-3: 12px;
  --size-4-4: 16px;
  --size-4-5: 20px;
  --size-4-6: 24px;
  --size-4-8: 32px;
  --size-4-12: 48px;
  --size-4-16: 64px;
  --size-4-18: 72px;
  /* Sidebar */
  --sidebar-markdown-font-size: var(--font-small);
  --sidebar-tab-text-display: none;
  /* Sliders */
  --slider-thumb-height: 18px;
  --slider-thumb-width: 18px;
  --slider-thumb-y: -6px;
  --slider-thumb-radius: 50%;
  --slider-s-thumb-size-: 15px;
  --slider-s-thumb-position: -5px;
  /* Status bar */
  --status-bar-background: var(--background-secondary);
  --status-bar-border-color: var(--divider-color);
  --status-bar-border-width: 1px 0 0 1px;
  --status-bar-font-size: var(--font-ui-smaller);
  --status-bar-text-color: var(--text-muted);
  --status-bar-position: fixed;
  --status-bar-radius: var(--radius-m) 0 0 0;
  /* Tabs */
  --tab-background-active: var(--background-primary);
  --tab-text-color: var(--text-faint);
  --tab-text-color-focused: var(--text-muted);
  --tab-text-color-focused-active: var(--text-normal);
  --tab-font-size: var(--font-ui-small);
  --tab-font-weight: inherit;
  --tab-container-background: var(--background-secondary);
  --tab-divider-color: var(--background-modifier-border-hover);
  --tab-outline-color: var(--divider-color);
  --tab-outline-width: 1px;
  --tab-curve: 6px;
  --tab-radius: var(--radius-s);
  --tab-radius-active: 6px 6px 0 0;
  /* Tables */
  --table-background: transparent;
  --table-border-width: 1px;
  --table-border-color: var(--background-modifier-border);
  --table-white-space: normal;
  --table-header-background: var(--table-background);
  --table-header-background-hover: inherit;
  --table-header-border-width: var(--table-border-width);
  --table-header-border-color: var(--table-border-color);
  --table-header-font: inherit;
  --table-header-size: var(--font-smaller);
  --table-header-weight: var(--font-normal);
  --table-header-color: var(--text-muted);
  --table-text-size: inherit;
  --table-text-color: inherit;
  --table-column-max-width: none;
  --table-column-alt-background: var(--table-background);
  --table-column-first-border-width: var(--table-border-width);
  --table-column-last-border-width: var(--table-border-width);
  --table-row-background-hover: var(--table-background);
  --table-row-alt-background: var(--table-background);
  --table-row-last-border-width: var(--table-border-width);
  /* Tags */
  --tag-size: var(--font-smaller);
  --tag-color: var(--text-accent);
  --tag-color-hover: var(--text-accent);
  --tag-decoration: none;
  --tag-decoration-hover: none;
  --tag-background: hsla(var(--interactive-accent-hsl), 0.1);
  --tag-background-hover: hsla(var(--interactive-accent-hsl), 0.2);
  --tag-border-color: hsla(var(--interactive-accent-hsl), 0.15);
  --tag-border-color-hover: hsla(var(--interactive-accent-hsl), 0.15);
  --tag-border-width: 0px;
  --tag-padding-x: 0.65em;
  --tag-padding-y: 0.25em;
  --tag-radius: 2em;
  /* Window frame */
  --titlebar-background: var(--background-secondary);
  --titlebar-background-focused: var(--background-secondary-alt);
  --titlebar-border-width: 0px;
  --titlebar-border-color: var(--background-modifier-border);
  --titlebar-text-color: var(--text-muted);
  --titlebar-text-color-focused: var(--text-normal);
  --titlebar-text-color-highlighted: var(--text-accent-hover);
  --titlebar-text-weight: var(--font-bold);
  /* Toggles */
  --toggle-border-width: 2px;
  --toggle-width: 40px;
  --toggle-radius: 18px;
  --toggle-thumb-color: white;
  --toggle-thumb-radius: 18px;
  --toggle-thumb-height: 18px;
  --toggle-thumb-width: 18px;
  --toggle-s-border-width: 2px;
  --toggle-s-width: 34px;
  --toggle-s-thumb-height: 15px;
  --toggle-s-thumb-width: 15px;
  /* Vault name */
  --vault-name-font-size: var(--font-ui-small);
  --vault-name-font-weight: var(--font-medium);
  --vault-name-color: var(--text-normal);
  /* Color mappings ------------------------ */
  /* Accent HSL values */
  --accent-h: 254;
  --accent-s: 80%;
  --accent-l: 68%;
  /* Backgrounds */
  --background-primary: var(--color-base-00);
  --background-primary-alt: var(--color-base-10);
  --background-secondary: var(--color-base-20);
  --background-modifier-hover: rgba(var(--mono-rgb-100), 0.075);
  --background-modifier-active-hover: hsla(var(--interactive-accent-hsl), 0.15);
  --background-modifier-border: var(--color-base-30);
  --background-modifier-border-hover: var(--color-base-35);
  --background-modifier-border-focus: var(--color-base-40);
  --background-modifier-error-rgb: var(--color-red-rgb);
  --background-modifier-error: var(--color-red);
  --background-modifier-error-hover: var(--color-red);
  --background-modifier-success-rgb: var(--color-green-rgb);
  --background-modifier-success: var(--color-green);
  --background-modifier-message: rgba(0, 0, 0, 0.9);
  /* Inputs */
  --background-modifier-form-field: var(--color-base-00);
  /* Text */
  --text-normal: var(--color-base-100);
  --text-muted: var(--color-base-70);
  --text-faint: var(--color-base-50);
  --text-on-accent: white;
  --text-error: var(--color-red);
  --text-success: var(--color-green);
  --text-selection: hsla(var(--color-accent-hsl), 0.2);
  --text-accent: var(--color-accent);
  --text-accent-hover: var(--color-accent-2);
  --interactive-normal: var(--color-base-00);
  --interactive-hover: var(--color-base-10);
  --interactive-accent-hsl: var(--color-accent-hsl);
  --interactive-accent: var(--color-accent-1);
  --interactive-accent-hover: var(--color-accent-2);
}
.theme-light {
  color-scheme: light;
  --highlight-mix-blend-mode: darken;
  --opacity-translucency: 0.6;
  --mono-rgb-0: 255, 255, 255;
  --mono-rgb-100: 0, 0, 0;
  --color-red-rgb: 228, 55, 75;
  --color-red: #E4374B;
  --color-green-rgb: 12, 181, 79;
  --color-green: #0cb54f;
  --color-orange: #d96c00;
  --color-yellow: #BD8E37;
  --color-cyan: #2db7b5;
  --color-blue: #086DDD;
  --color-purple: #876be0;
  --color-pink: #C32B74;
  --color-base-00: #ffffff;
  --color-base-05: #fcfcfc;
  --color-base-10: #fafafa;
  --color-base-20: #f6f6f6;
  --color-base-25: #e3e3e3;
  --color-base-30: #e0e0e0;
  --color-base-35: #d4d4d4;
  --color-base-40: #bdbdbd;
  --color-base-50: #ababab;
  --color-base-60: #707070;
  --color-base-70: #5a5a5a;
  --color-base-100: #222222;
  --color-accent-hsl: var(--accent-h),
			var(--accent-s),
			var(--accent-l);
  --color-accent: hsl(var(--accent-h), var(--accent-s), var(--accent-l));
  --color-accent-1: hsl(var(--accent-h), var(--accent-s), calc(var(--accent-l) + 2.5%));
  --color-accent-2: hsl(var(--accent-h), var(--accent-s), calc(var(--accent-l) + 5%));
  --background-secondary-alt: var(--color-base-05);
  --background-modifier-box-shadow: rgba(0, 0, 0, 0.1);
  --background-modifier-cover: rgba(220, 220, 220, 0.4);
  --text-highlight-bg: rgba(255, 208, 0, 0.4);
  --text-highlight-bg-active: rgba(255, 128, 0, 0.4);
  --input-shadow: inset 0 0 0 1px rgba(0, 0, 0, 0.12),
		0 2px 3px 0 rgba(0,0,0,.05),
		0 1px 1.5px 0 rgba(0,0,0,.03),
		0 1px 2px 0 rgba(0,0,0,.04),
		0 0 0 0 transparent;
  --input-shadow-hover: inset 0 0 0 1px rgba(0, 0, 0, 0.17),
		0 2px 3px 0 rgba(0,0,0,.1),
		0 1px 1.5px 0 rgba(0,0,0,.03),
		0 1px 2px 0 rgba(0,0,0,.04),
		0 0 0 0 transparent;
  --shadow-s: 0px 1px 2px rgba(0, 0, 0, 0.028),
		0px 3.4px 6.7px rgba(0, 0, 0, .042),
		0px 15px 30px rgba(0, 0, 0, .07);
  --shadow-l: 0px 1.8px 7.3px rgba(0, 0, 0, 0.071),
		0px 6.3px 24.7px rgba(0, 0, 0, 0.112),
		0px 30px 90px rgba(0, 0, 0, 0.2);
}
.theme-dark {
  color-scheme: dark;
  --highlight-mix-blend-mode: lighten;
  --opacity-translucency: 0.75;
  --mono-rgb-0: 0, 0, 0;
  --mono-rgb-100: 255, 255, 255;
  --color-red-rgb: 251, 70, 76;
  --color-red: #fb464c;
  --color-green-rgb: 68, 207, 110;
  --color-green: #44CF6E;
  --color-orange: #E9973F;
  --color-yellow: #E0DE71;
  --color-cyan: #53DFDD;
  --color-blue: #027aff;
  --color-purple: #a882ff;
  --color-pink: #FA99CD;
  --color-base-00: #1e1e1e;
  --color-base-10: #242424;
  --color-base-20: #262626;
  --color-base-25: #2a2a2a;
  --color-base-30: #363636;
  --color-base-35: #3F3F3F;
  --color-base-40: #555;
  --color-base-50: #666;
  --color-base-60: #999;
  --color-base-70: #bababa;
  --color-base-100: #dadada;
  --color-accent-hsl: var(--accent-h),
			var(--accent-s),
			var(--accent-l);
  --color-accent: hsl(var(--accent-h), var(--accent-s), var(--accent-l));
  --color-accent-1: hsl(var(--accent-h), var(--accent-s), calc(var(--accent-l) - 3.8%));
  --color-accent-2: hsl(var(--accent-h), var(--accent-s), calc(var(--accent-l) + 3.8%));
  --background-modifier-form-field: var(--color-base-25);
  --background-secondary-alt: var(--color-base-30);
  --interactive-normal: var(--color-base-30);
  --interactive-hover: var(--color-base-35);
  --background-modifier-box-shadow: rgba(0, 0, 0, 0.3);
  --background-modifier-cover: rgba(10, 10, 10, 0.4);
  --text-highlight-bg: rgba(255, 208, 0, 0.4);
  --text-highlight-bg-active: rgba(255, 128, 0, 0.4);
  --text-selection: hsla(var(--interactive-accent-hsl), 0.25);
  --input-shadow: inset 0 0.5px 0.5px 0.5px rgba(255, 255, 255, 0.09),
		0 2px 4px 0 rgba(0,0,0,.15),
		0 1px 1.5px 0 rgba(0,0,0,.1),
		0 1px 2px 0 rgba(0,0,0,.2),
		0 0 0 0 transparent;
  --input-shadow-hover: inset 0 0.5px 1px 0.5px rgba(255, 255, 255, 0.16),
		0 2px 3px 0 rgba(0,0,0,.3),
		0 1px 1.5px 0 rgba(0,0,0,.2),
		0 1px 2px 0 rgba(0,0,0,.4),
		0 0 0 0 transparent;
  --shadow-s: 0px 1px 2px rgba(0, 0, 0, 0.121),
		0px 3.4px 6.7px rgba(0, 0, 0, 0.179),
		0px 15px 30px rgba(0, 0, 0, 0.3);
  --shadow-l: 0px 1.8px 7.3px rgba(0, 0, 0, 0.071),
		0px 6.3px 24.7px rgba(0, 0, 0, 0.112),
		0px 30px 90px rgba(0, 0, 0, 0.2);
}
```
