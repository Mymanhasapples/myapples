<!--HTTPS only...--><html><head><style id="ace-monokai">.ace-monokai .ace_gutter {background: #2F3129;color: #8F908A}.ace-monokai .ace_print-margin {width: 1px;background: #555651}.ace-monokai {background-color: #272822;color: #F8F8F2}.ace-monokai .ace_cursor {color: #F8F8F0}.ace-monokai .ace_marker-layer .ace_selection {background: #49483E}.ace-monokai.ace_multiselect .ace_selection.ace_start {box-shadow: 0 0 3px 0px #272822;}.ace-monokai .ace_marker-layer .ace_step {background: rgb(102, 82, 0)}.ace-monokai .ace_marker-layer .ace_bracket {margin: -1px 0 0 -1px;border: 1px solid #49483E}.ace-monokai .ace_marker-layer .ace_active-line {background: #202020}.ace-monokai .ace_gutter-active-line {background-color: #272727}.ace-monokai .ace_marker-layer .ace_selected-word {border: 1px solid #49483E}.ace-monokai .ace_invisible {color: #52524d}.ace-monokai .ace_entity.ace_name.ace_tag,.ace-monokai .ace_keyword,.ace-monokai .ace_meta.ace_tag,.ace-monokai .ace_storage {color: #F92672}.ace-monokai .ace_punctuation,.ace-monokai .ace_punctuation.ace_tag {color: #fff}.ace-monokai .ace_constant.ace_character,.ace-monokai .ace_constant.ace_language,.ace-monokai .ace_constant.ace_numeric,.ace-monokai .ace_constant.ace_other {color: #AE81FF}.ace-monokai .ace_invalid {color: #F8F8F0;background-color: #F92672}.ace-monokai .ace_invalid.ace_deprecated {color: #F8F8F0;background-color: #AE81FF}.ace-monokai .ace_support.ace_constant,.ace-monokai .ace_support.ace_function {color: #66D9EF}.ace-monokai .ace_fold {background-color: #A6E22E;border-color: #F8F8F2}.ace-monokai .ace_storage.ace_type,.ace-monokai .ace_support.ace_class,.ace-monokai .ace_support.ace_type {font-style: italic;color: #66D9EF}.ace-monokai .ace_entity.ace_name.ace_function,.ace-monokai .ace_entity.ace_other,.ace-monokai .ace_entity.ace_other.ace_attribute-name,.ace-monokai .ace_variable {color: #A6E22E}.ace-monokai .ace_variable.ace_parameter {font-style: italic;color: #FD971F}.ace-monokai .ace_string {color: #E6DB74}.ace-monokai .ace_comment {color: #75715E}.ace-monokai .ace_indent-guide {background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAACCAYAAACZgbYnAAAAEklEQVQImWPQ0FD0ZXBzd/wPAAjVAoxeSgNeAAAAAElFTkSuQmCC) right repeat-y}
/*# sourceURL=ace/css/ace-monokai */</style><style>    .error_widget_wrapper {        background: inherit;        color: inherit;        border:none    }    .error_widget {        border-top: solid 2px;        border-bottom: solid 2px;        margin: 5px 0;        padding: 10px 40px;        white-space: pre-wrap;    }    .error_widget.ace_error, .error_widget_arrow.ace_error{        border-color: #ff5a5a    }    .error_widget.ace_warning, .error_widget_arrow.ace_warning{        border-color: #F1D817    }    .error_widget.ace_info, .error_widget_arrow.ace_info{        border-color: #5a5a5a    }    .error_widget.ace_ok, .error_widget_arrow.ace_ok{        border-color: #5aaa5a    }    .error_widget_arrow {        position: absolute;        border: solid 5px;        border-top-color: transparent!important;        border-right-color: transparent!important;        border-left-color: transparent!important;        top: -5px;    }</style><style id="ace-tm">.ace-tm .ace_gutter {background: #f0f0f0;color: #333;}.ace-tm .ace_print-margin {width: 1px;background: #e8e8e8;}.ace-tm .ace_fold {background-color: #6B72E6;}.ace-tm {background-color: #FFFFFF;color: black;}.ace-tm .ace_cursor {color: black;}.ace-tm .ace_invisible {color: rgb(191, 191, 191);}.ace-tm .ace_storage,.ace-tm .ace_keyword {color: blue;}.ace-tm .ace_constant {color: rgb(197, 6, 11);}.ace-tm .ace_constant.ace_buildin {color: rgb(88, 72, 246);}.ace-tm .ace_constant.ace_language {color: rgb(88, 92, 246);}.ace-tm .ace_constant.ace_library {color: rgb(6, 150, 14);}.ace-tm .ace_invalid {background-color: rgba(255, 0, 0, 0.1);color: red;}.ace-tm .ace_support.ace_function {color: rgb(60, 76, 114);}.ace-tm .ace_support.ace_constant {color: rgb(6, 150, 14);}.ace-tm .ace_support.ace_type,.ace-tm .ace_support.ace_class {color: rgb(109, 121, 222);}.ace-tm .ace_keyword.ace_operator {color: rgb(104, 118, 135);}.ace-tm .ace_string {color: rgb(3, 106, 7);}.ace-tm .ace_comment {color: rgb(76, 136, 107);}.ace-tm .ace_comment.ace_doc {color: rgb(0, 102, 255);}.ace-tm .ace_comment.ace_doc.ace_tag {color: rgb(128, 159, 191);}.ace-tm .ace_constant.ace_numeric {color: rgb(0, 0, 205);}.ace-tm .ace_variable {color: rgb(49, 132, 149);}.ace-tm .ace_xml-pe {color: rgb(104, 104, 91);}.ace-tm .ace_entity.ace_name.ace_function {color: #0000A2;}.ace-tm .ace_heading {color: rgb(12, 7, 255);}.ace-tm .ace_list {color:rgb(185, 6, 144);}.ace-tm .ace_meta.ace_tag {color:rgb(0, 22, 142);}.ace-tm .ace_string.ace_regex {color: rgb(255, 0, 0)}.ace-tm .ace_marker-layer .ace_selection {background: rgb(181, 213, 255);}.ace-tm.ace_multiselect .ace_selection.ace_start {box-shadow: 0 0 3px 0px white;}.ace-tm .ace_marker-layer .ace_step {background: rgb(252, 255, 0);}.ace-tm .ace_marker-layer .ace_stack {background: rgb(164, 229, 101);}.ace-tm .ace_marker-layer .ace_bracket {margin: -1px 0 0 -1px;border: 1px solid rgb(192, 192, 192);}.ace-tm .ace_marker-layer .ace_active-line {background: rgba(0, 0, 0, 0.07);}.ace-tm .ace_gutter-active-line {background-color : #dcdcdc;}.ace-tm .ace_marker-layer .ace_selected-word {background: rgb(250, 250, 255);border: 1px solid rgb(200, 200, 250);}.ace-tm .ace_indent-guide {background: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAACCAYAAACZgbYnAAAAE0lEQVQImWP4////f4bLly//BwAmVgd1/w11/gAAAABJRU5ErkJggg==") right repeat-y;}
/*# sourceURL=ace/css/ace-tm */</style><style id="ace_editor.css">.ace_br1 {border-top-left-radius    : 3px;}.ace_br2 {border-top-right-radius   : 3px;}.ace_br3 {border-top-left-radius    : 3px; border-top-right-radius:    3px;}.ace_br4 {border-bottom-right-radius: 3px;}.ace_br5 {border-top-left-radius    : 3px; border-bottom-right-radius: 3px;}.ace_br6 {border-top-right-radius   : 3px; border-bottom-right-radius: 3px;}.ace_br7 {border-top-left-radius    : 3px; border-top-right-radius:    3px; border-bottom-right-radius: 3px;}.ace_br8 {border-bottom-left-radius : 3px;}.ace_br9 {border-top-left-radius    : 3px; border-bottom-left-radius:  3px;}.ace_br10{border-top-right-radius   : 3px; border-bottom-left-radius:  3px;}.ace_br11{border-top-left-radius    : 3px; border-top-right-radius:    3px; border-bottom-left-radius:  3px;}.ace_br12{border-bottom-right-radius: 3px; border-bottom-left-radius:  3px;}.ace_br13{border-top-left-radius    : 3px; border-bottom-right-radius: 3px; border-bottom-left-radius:  3px;}.ace_br14{border-top-right-radius   : 3px; border-bottom-right-radius: 3px; border-bottom-left-radius:  3px;}.ace_br15{border-top-left-radius    : 3px; border-top-right-radius:    3px; border-bottom-right-radius: 3px; border-bottom-left-radius: 3px;}.ace_editor {position: relative;overflow: hidden;font: 12px/normal 'Monaco', 'Menlo', 'Ubuntu Mono', 'Consolas', 'source-code-pro', monospace;direction: ltr;text-align: left;-webkit-tap-highlight-color: rgba(0, 0, 0, 0);}.ace_scroller {position: absolute;overflow: hidden;top: 0;bottom: 0;background-color: inherit;-ms-user-select: none;-moz-user-select: none;-webkit-user-select: none;user-select: none;cursor: text;}.ace_content {position: absolute;box-sizing: border-box;min-width: 100%;contain: style size layout;}.ace_dragging .ace_scroller:before{position: absolute;top: 0;left: 0;right: 0;bottom: 0;content: '';background: rgba(250, 250, 250, 0.01);z-index: 1000;}.ace_dragging.ace_dark .ace_scroller:before{background: rgba(0, 0, 0, 0.01);}.ace_selecting, .ace_selecting * {cursor: text !important;}.ace_gutter {position: absolute;overflow : hidden;width: auto;top: 0;bottom: 0;left: 0;cursor: default;z-index: 4;-ms-user-select: none;-moz-user-select: none;-webkit-user-select: none;user-select: none;contain: style size layout;}.ace_gutter-active-line {position: absolute;left: 0;right: 0;}.ace_scroller.ace_scroll-left {box-shadow: 17px 0 16px -16px rgba(0, 0, 0, 0.4) inset;}.ace_gutter-cell {position: absolute;top: 0;left: 0;right: 0;padding-left: 19px;padding-right: 6px;background-repeat: no-repeat;}.ace_gutter-cell.ace_error {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAABOFBMVEX/////////QRswFAb/Ui4wFAYwFAYwFAaWGAfDRymzOSH/PxswFAb/SiUwFAYwFAbUPRvjQiDllog5HhHdRybsTi3/Tyv9Tir+Syj/UC3////XurebMBIwFAb/RSHbPx/gUzfdwL3kzMivKBAwFAbbvbnhPx66NhowFAYwFAaZJg8wFAaxKBDZurf/RB6mMxb/SCMwFAYwFAbxQB3+RB4wFAb/Qhy4Oh+4QifbNRcwFAYwFAYwFAb/QRzdNhgwFAYwFAbav7v/Uy7oaE68MBK5LxLewr/r2NXewLswFAaxJw4wFAbkPRy2PyYwFAaxKhLm1tMwFAazPiQwFAaUGAb/QBrfOx3bvrv/VC/maE4wFAbRPBq6MRO8Qynew8Dp2tjfwb0wFAbx6eju5+by6uns4uH9/f36+vr/GkHjAAAAYnRSTlMAGt+64rnWu/bo8eAA4InH3+DwoN7j4eLi4xP99Nfg4+b+/u9B/eDs1MD1mO7+4PHg2MXa347g7vDizMLN4eG+Pv7i5evs/v79yu7S3/DV7/498Yv24eH+4ufQ3Ozu/v7+y13sRqwAAADLSURBVHjaZc/XDsFgGIBhtDrshlitmk2IrbHFqL2pvXf/+78DPokj7+Fz9qpU/9UXJIlhmPaTaQ6QPaz0mm+5gwkgovcV6GZzd5JtCQwgsxoHOvJO15kleRLAnMgHFIESUEPmawB9ngmelTtipwwfASilxOLyiV5UVUyVAfbG0cCPHig+GBkzAENHS0AstVF6bacZIOzgLmxsHbt2OecNgJC83JERmePUYq8ARGkJx6XtFsdddBQgZE2nPR6CICZhawjA4Fb/chv+399kfR+MMMDGOQAAAABJRU5ErkJggg==");background-repeat: no-repeat;background-position: 2px center;}.ace_gutter-cell.ace_warning {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAAmVBMVEX///8AAAD///8AAAAAAABPSzb/5sAAAAB/blH/73z/ulkAAAAAAAD85pkAAAAAAAACAgP/vGz/rkDerGbGrV7/pkQICAf////e0IsAAAD/oED/qTvhrnUAAAD/yHD/njcAAADuv2r/nz//oTj/p064oGf/zHAAAAA9Nir/tFIAAAD/tlTiuWf/tkIAAACynXEAAAAAAAAtIRW7zBpBAAAAM3RSTlMAABR1m7RXO8Ln31Z36zT+neXe5OzooRDfn+TZ4p3h2hTf4t3k3ucyrN1K5+Xaks52Sfs9CXgrAAAAjklEQVR42o3PbQ+CIBQFYEwboPhSYgoYunIqqLn6/z8uYdH8Vmdnu9vz4WwXgN/xTPRD2+sgOcZjsge/whXZgUaYYvT8QnuJaUrjrHUQreGczuEafQCO/SJTufTbroWsPgsllVhq3wJEk2jUSzX3CUEDJC84707djRc5MTAQxoLgupWRwW6UB5fS++NV8AbOZgnsC7BpEAAAAABJRU5ErkJggg==");background-position: 2px center;}.ace_gutter-cell.ace_info {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAAAAAA6mKC9AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAAJ0Uk5TAAB2k804AAAAPklEQVQY02NgIB68QuO3tiLznjAwpKTgNyDbMegwisCHZUETUZV0ZqOquBpXj2rtnpSJT1AEnnRmL2OgGgAAIKkRQap2htgAAAAASUVORK5CYII=");background-position: 2px center;}.ace_dark .ace_gutter-cell.ace_info {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQBAMAAADt3eJSAAAAJFBMVEUAAAChoaGAgIAqKiq+vr6tra1ZWVmUlJSbm5s8PDxubm56enrdgzg3AAAAAXRSTlMAQObYZgAAAClJREFUeNpjYMAPdsMYHegyJZFQBlsUlMFVCWUYKkAZMxZAGdxlDMQBAG+TBP4B6RyJAAAAAElFTkSuQmCC");}.ace_scrollbar {contain: strict;position: absolute;right: 0;bottom: 0;z-index: 6;}.ace_scrollbar-inner {position: absolute;cursor: text;left: 0;top: 0;}.ace_scrollbar-v{overflow-x: hidden;overflow-y: scroll;top: 0;}.ace_scrollbar-h {overflow-x: scroll;overflow-y: hidden;left: 0;}.ace_print-margin {position: absolute;height: 100%;}.ace_text-input {position: absolute;z-index: 0;width: 0.5em;height: 1em;opacity: 0;background: transparent;-moz-appearance: none;appearance: none;border: none;resize: none;outline: none;overflow: hidden;font: inherit;padding: 0 1px;margin: 0 -1px;contain: strict;-ms-user-select: text;-moz-user-select: text;-webkit-user-select: text;user-select: text;white-space: pre!important;}.ace_text-input.ace_composition {background: transparent;color: inherit;z-index: 1000;opacity: 1;}.ace_composition_placeholder { color: transparent }.ace_composition_marker { border-bottom: 1px solid;position: absolute;border-radius: 0;margin-top: 1px;}[ace_nocontext=true] {transform: none!important;filter: none!important;perspective: none!important;clip-path: none!important;mask : none!important;contain: none!important;perspective: none!important;mix-blend-mode: initial!important;z-index: auto;}.ace_layer {z-index: 1;position: absolute;overflow: hidden;word-wrap: normal;white-space: pre;height: 100%;width: 100%;box-sizing: border-box;pointer-events: none;}.ace_gutter-layer {position: relative;width: auto;text-align: right;pointer-events: auto;height: 1000000px;contain: style size layout;}.ace_text-layer {font: inherit !important;position: absolute;height: 1000000px;width: 1000000px;contain: style size layout;}.ace_text-layer > .ace_line, .ace_text-layer > .ace_line_group {contain: style size layout;position: absolute;top: 0;left: 0;right: 0;}.ace_hidpi .ace_text-layer,.ace_hidpi .ace_gutter-layer,.ace_hidpi .ace_content,.ace_hidpi .ace_gutter {contain: strict;will-change: transform;}.ace_hidpi .ace_text-layer > .ace_line, .ace_hidpi .ace_text-layer > .ace_line_group {contain: strict;}.ace_cjk {display: inline-block;text-align: center;}.ace_cursor-layer {z-index: 4;}.ace_cursor {z-index: 4;position: absolute;box-sizing: border-box;border-left: 2px solid;transform: translatez(0);}.ace_multiselect .ace_cursor {border-left-width: 1px;}.ace_slim-cursors .ace_cursor {border-left-width: 1px;}.ace_overwrite-cursors .ace_cursor {border-left-width: 0;border-bottom: 1px solid;}.ace_hidden-cursors .ace_cursor {opacity: 0.2;}.ace_smooth-blinking .ace_cursor {transition: opacity 0.18s;}.ace_animate-blinking .ace_cursor {animation-duration: 1000ms;animation-timing-function: step-end;animation-name: blink-ace-animate;animation-iteration-count: infinite;}.ace_animate-blinking.ace_smooth-blinking .ace_cursor {animation-duration: 1000ms;animation-timing-function: ease-in-out;animation-name: blink-ace-animate-smooth;}@keyframes blink-ace-animate {from, to { opacity: 1; }60% { opacity: 0; }}@keyframes blink-ace-animate-smooth {from, to { opacity: 1; }45% { opacity: 1; }60% { opacity: 0; }85% { opacity: 0; }}.ace_marker-layer .ace_step, .ace_marker-layer .ace_stack {position: absolute;z-index: 3;}.ace_marker-layer .ace_selection {position: absolute;z-index: 5;}.ace_marker-layer .ace_bracket {position: absolute;z-index: 6;}.ace_marker-layer .ace_active-line {position: absolute;z-index: 2;}.ace_marker-layer .ace_selected-word {position: absolute;z-index: 4;box-sizing: border-box;}.ace_line .ace_fold {box-sizing: border-box;display: inline-block;height: 11px;margin-top: -2px;vertical-align: middle;background-image:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAAAJCAYAAADU6McMAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAJpJREFUeNpi/P//PwOlgAXGYGRklAVSokD8GmjwY1wasKljQpYACtpCFeADcHVQfQyMQAwzwAZI3wJKvCLkfKBaMSClBlR7BOQikCFGQEErIH0VqkabiGCAqwUadAzZJRxQr/0gwiXIal8zQQPnNVTgJ1TdawL0T5gBIP1MUJNhBv2HKoQHHjqNrA4WO4zY0glyNKLT2KIfIMAAQsdgGiXvgnYAAAAASUVORK5CYII="),url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAA3CAYAAADNNiA5AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAACJJREFUeNpi+P//fxgTAwPDBxDxD078RSX+YeEyDFMCIMAAI3INmXiwf2YAAAAASUVORK5CYII=");background-repeat: no-repeat, repeat-x;background-position: center center, top left;color: transparent;border: 1px solid black;border-radius: 2px;cursor: pointer;pointer-events: auto;}.ace_dark .ace_fold {}.ace_fold:hover{background-image:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAAAJCAYAAADU6McMAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAJpJREFUeNpi/P//PwOlgAXGYGRklAVSokD8GmjwY1wasKljQpYACtpCFeADcHVQfQyMQAwzwAZI3wJKvCLkfKBaMSClBlR7BOQikCFGQEErIH0VqkabiGCAqwUadAzZJRxQr/0gwiXIal8zQQPnNVTgJ1TdawL0T5gBIP1MUJNhBv2HKoQHHjqNrA4WO4zY0glyNKLT2KIfIMAAQsdgGiXvgnYAAAAASUVORK5CYII="),url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAA3CAYAAADNNiA5AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAACBJREFUeNpi+P//fz4TAwPDZxDxD5X4i5fLMEwJgAADAEPVDbjNw87ZAAAAAElFTkSuQmCC");}.ace_tooltip {background-color: #FFF;background-image: linear-gradient(to bottom, transparent, rgba(0, 0, 0, 0.1));border: 1px solid gray;border-radius: 1px;box-shadow: 0 1px 2px rgba(0, 0, 0, 0.3);color: black;max-width: 100%;padding: 3px 4px;position: fixed;z-index: 999999;box-sizing: border-box;cursor: default;white-space: pre;word-wrap: break-word;line-height: normal;font-style: normal;font-weight: normal;letter-spacing: normal;pointer-events: none;}.ace_folding-enabled > .ace_gutter-cell {padding-right: 13px;}.ace_fold-widget {box-sizing: border-box;margin: 0 -12px 0 1px;display: none;width: 11px;vertical-align: top;background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAANElEQVR42mWKsQ0AMAzC8ixLlrzQjzmBiEjp0A6WwBCSPgKAXoLkqSot7nN3yMwR7pZ32NzpKkVoDBUxKAAAAABJRU5ErkJggg==");background-repeat: no-repeat;background-position: center;border-radius: 3px;border: 1px solid transparent;cursor: pointer;}.ace_folding-enabled .ace_fold-widget {display: inline-block;   }.ace_fold-widget.ace_end {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAANElEQVR42m3HwQkAMAhD0YzsRchFKI7sAikeWkrxwScEB0nh5e7KTPWimZki4tYfVbX+MNl4pyZXejUO1QAAAABJRU5ErkJggg==");}.ace_fold-widget.ace_closed {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAMAAAAGCAYAAAAG5SQMAAAAOUlEQVR42jXKwQkAMAgDwKwqKD4EwQ26sSOkVWjgIIHAzPiCgaqiqnJHZnKICBERHN194O5b9vbLuAVRL+l0YWnZAAAAAElFTkSuQmCCXA==");}.ace_fold-widget:hover {border: 1px solid rgba(0, 0, 0, 0.3);background-color: rgba(255, 255, 255, 0.2);box-shadow: 0 1px 1px rgba(255, 255, 255, 0.7);}.ace_fold-widget:active {border: 1px solid rgba(0, 0, 0, 0.4);background-color: rgba(0, 0, 0, 0.05);box-shadow: 0 1px 1px rgba(255, 255, 255, 0.8);}.ace_dark .ace_fold-widget {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAAHklEQVQIW2P4//8/AzoGEQ7oGCaLLAhWiSwB146BAQCSTPYocqT0AAAAAElFTkSuQmCC");}.ace_dark .ace_fold-widget.ace_end {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAAH0lEQVQIW2P4//8/AxQ7wNjIAjDMgC4AxjCVKBirIAAF0kz2rlhxpAAAAABJRU5ErkJggg==");}.ace_dark .ace_fold-widget.ace_closed {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAMAAAAFCAYAAACAcVaiAAAAHElEQVQIW2P4//+/AxAzgDADlOOAznHAKgPWAwARji8UIDTfQQAAAABJRU5ErkJggg==");}.ace_dark .ace_fold-widget:hover {box-shadow: 0 1px 1px rgba(255, 255, 255, 0.2);background-color: rgba(255, 255, 255, 0.1);}.ace_dark .ace_fold-widget:active {box-shadow: 0 1px 1px rgba(255, 255, 255, 0.2);}.ace_inline_button {border: 1px solid lightgray;display: inline-block;margin: -1px 8px;padding: 0 5px;pointer-events: auto;cursor: pointer;}.ace_inline_button:hover {border-color: gray;background: rgba(200,200,200,0.2);display: inline-block;pointer-events: auto;}.ace_fold-widget.ace_invalid {background-color: #FFB4B4;border-color: #DE5555;}.ace_fade-fold-widgets .ace_fold-widget {transition: opacity 0.4s ease 0.05s;opacity: 0;}.ace_fade-fold-widgets:hover .ace_fold-widget {transition: opacity 0.05s ease 0.05s;opacity:1;}.ace_underline {text-decoration: underline;}.ace_bold {font-weight: bold;}.ace_nobold .ace_bold {font-weight: normal;}.ace_italic {font-style: italic;}.ace_error-marker {background-color: rgba(255, 0, 0,0.2);position: absolute;z-index: 9;}.ace_highlight-marker {background-color: rgba(255, 255, 0,0.2);position: absolute;z-index: 8;}.ace_text-input-ios {position: absolute !important;top: -100000px !important;left: -100000px !important;}
/*# sourceURL=ace/css/ace_editor.css */</style>

<script src="https://cdnjs.cloudflare.com/ajax/libs/ace/1.4.1/ace.js"> </script>

<style>

html,body { margin:0; padding:0; height:100%; width:100%; overflow: hidden;}



#editor {

    height: 100%;

    width:50%;

    display:inline-block;

}



#container {

	height:100%;

	width:auto;

  white-space : nowrap; 

  overflow : hidden;

  position:relative;

}



#iframe {

	height:100%;

	display:inline-block;

	width:50%;

}



/* disable tag matching */

.ace_editor .ace_marker-layer .ace_bracket { display: none }



</style>

<script src="https://cdnjs.cloudflare.com/ajax/libs/ace/1.4.1/theme-monokai.js"></script><script src="https://cdnjs.cloudflare.com/ajax/libs/ace/1.4.1/mode-html.js"></script></head>

<body onload="ready()">



	<div id="container">



  <div id="editor" class=" ace_editor ace_hidpi ace_dark ace-monokai" style="font-size: 16pt;"><textarea class="ace_text-input" wrap="off" autocorrect="off" autocapitalize="off" spellcheck="false" style="opacity: 0; font-size: 1px; transform: translate(170px, 232px); height: 1px; width: 1px;"></textarea><div class="ace_gutter" aria-hidden="true" style="left: 0px; width: 59px; display: none;"><div class="ace_layer ace_gutter-layer ace_folding-enabled" style="height: 1e+06px; transform: translate(0px, 0px); width: 59px;"><div class="ace_gutter-cell " style="height: 29px; top: 0px;">1<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 29px;">2<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 58px;">3<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 87px;">4<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 116px;">5<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 145px;">6<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 174px;">7<span style="display: none;"></span></div><div class="ace_gutter-active-line ace_gutter-cell " style="height: 29px; top: 203px;">8<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 232px;">9<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 261px;">10<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 290px;">11<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 319px;">12<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 348px;">13<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 377px;">14<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 406px;">15<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 435px;">16<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 464px;">17<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 493px;">18<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 522px;">19<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 551px;">20<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 580px;">21<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 609px;">22<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 638px;">23<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 667px;">24<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 696px;">25<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 725px;">26<span style="display: none;"></span></div><div class="ace_gutter-cell " style="height: 29px; top: 754px;">27<span style="display: none;"></span></div></div></div><div class="ace_scroller" style="left: 0px; right: 0px; bottom: 0px;"><div class="ace_content" style="transform: translate(0px, 0px); width: 878px; height: 1886px;"><div class="ace_layer ace_print-margin-layer"><div class="ace_print-margin" style="left: 1028px; visibility: hidden;"></div></div><div class="ace_layer ace_marker-layer"><div class="ace_active-line" style="height: 29px; top: 203px; left: 0px; right: 0px;"></div><div class="ace_bracket ace_start ace_br15" style="height: 29px; width: 12.8px; top: 464px; left: 4px;"></div></div><div class="ace_layer ace_text-layer" style="height: 1e+06px; margin: 0px 4px; transform: translate(0px, 0px);"><div class="ace_line" style="height: 29px; top: 0px;"><span class="ace_xml-pe ace_doctype ace_xml">&lt;!</span><span class="ace_xml-pe ace_doctype ace_xml">DOCTYPE</span><span class="ace_text ace_whitespace ace_xml"> </span><span class="ace_xml-pe ace_xml">html</span><span class="ace_xml-pe ace_doctype ace_xml">&gt;</span></div><div class="ace_line" style="height: 29px; top: 29px;"></div><div class="ace_line" style="height: 29px; top: 58px;"><span class="ace_meta ace_tag ace_punctuation ace_tag-open ace_xml">&lt;</span><span class="ace_meta ace_tag ace_tag-name ace_xml">html</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span></div><div class="ace_line" style="height: 29px; top: 87px;"><span class="ace_meta ace_tag ace_punctuation ace_tag-open ace_xml">&lt;</span><span class="ace_meta ace_tag ace_tag-name ace_xml">head</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span></div><div class="ace_line" style="height: 29px; top: 116px;"><span class="ace_meta ace_tag ace_punctuation ace_tag-open ace_xml">&lt;</span><span class="ace_meta ace_tag ace_tag-name ace_xml">meta</span><span class="ace_text ace_tag-whitespace ace_xml"> </span><span class="ace_entity ace_other ace_attribute-name ace_xml">name</span><span class="ace_keyword ace_operator ace_attribute-equals ace_xml">=</span><span class="ace_string ace_attribute-value ace_xml">"viewport"</span><span class="ace_text ace_tag-whitespace ace_xml"> </span><span class="ace_entity ace_other ace_attribute-name ace_xml">content</span><span class="ace_keyword ace_operator ace_attribute-equals ace_xml">=</span><span class="ace_string ace_attribute-value ace_xml">"width=device-width, initial-scale=1"</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span></div><div class="ace_line" style="height: 29px; top: 145px;"><span class="ace_meta ace_tag ace_punctuation ace_tag-open ace_xml">&lt;</span><span class="ace_meta ace_tag ace_style ace_tag-name ace_xml">style</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span></div><div class="ace_line" style="height: 29px; top: 174px;"><span class="ace_comment">/* The device with borders */</span></div><div class="ace_line" style="height: 29px; top: 203px;"><span class="ace_variable">.smartphone</span> <span class="ace_paren ace_lparen">{</span></div><div class="ace_line" style="height: 29px; top: 232px;">  <span class="ace_support ace_type">position</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_support ace_constant">relative</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 261px;">  <span class="ace_support ace_type">width</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">360</span><span class="ace_keyword">px</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 290px;">  <span class="ace_support ace_type">height</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">640</span><span class="ace_keyword">px</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 319px;">  <span class="ace_support ace_type">margin</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_support ace_constant">auto</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 348px;">  <span class="ace_support ace_type">border</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">16</span><span class="ace_keyword">px</span> <span class="ace_support ace_constant ace_color">black</span> <span class="ace_support ace_constant">solid</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 377px;">  <span class="ace_support ace_type">border-top-width</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">60</span><span class="ace_keyword">px</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 406px;">  <span class="ace_support ace_type">border-bottom-width</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">60</span><span class="ace_keyword">px</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 435px;">  <span class="ace_support ace_type">border-radius</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">36</span><span class="ace_keyword">px</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 464px;"><span class="ace_paren ace_rparen">}</span></div><div class="ace_line" style="height: 29px; top: 493px;"></div><div class="ace_line" style="height: 29px; top: 522px;"><span class="ace_comment">/* The horizontal line on the top of the device */</span></div><div class="ace_line" style="height: 29px; top: 551px;"><span class="ace_variable">.smartphone</span><span class="ace_string">:before</span> <span class="ace_paren ace_lparen">{</span></div><div class="ace_line" style="height: 29px; top: 580px;">  <span class="ace_support ace_type">content</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_string ace_start">'</span><span class="ace_string ace_end">'</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 609px;">  <span class="ace_support ace_type">display</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_support ace_constant">block</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 638px;">  <span class="ace_support ace_type">width</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">60</span><span class="ace_keyword">px</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 667px;">  <span class="ace_support ace_type">height</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">5</span><span class="ace_keyword">px</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 696px;">  <span class="ace_support ace_type">position</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_support ace_constant">absolute</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 725px;">  <span class="ace_support ace_type">top</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">-30</span><span class="ace_keyword">px</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 754px;">  <span class="ace_support ace_type">left</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">50</span><span class="ace_keyword">%</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 783px;">  <span class="ace_support ace_type">transform</span><span class="ace_punctuation ace_operator">:</span> translate(<span class="ace_constant ace_numeric">-50</span><span class="ace_keyword">%</span>, <span class="ace_constant ace_numeric">-50</span><span class="ace_keyword">%</span>)<span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 812px;">  <span class="ace_support ace_type">background</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">#333</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 841px;">  <span class="ace_support ace_type">border-radius</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">10</span><span class="ace_keyword">px</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 870px;"><span class="ace_paren ace_rparen">}</span></div><div class="ace_line" style="height: 29px; top: 899px;"></div><div class="ace_line" style="height: 29px; top: 928px;"><span class="ace_comment">/* The circle on the bottom of the device */</span></div><div class="ace_line" style="height: 29px; top: 957px;"><span class="ace_variable">.smartphone</span><span class="ace_string">:after</span> <span class="ace_paren ace_lparen">{</span></div><div class="ace_line" style="height: 29px; top: 986px;">  <span class="ace_support ace_type">content</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_string ace_start">'</span><span class="ace_string ace_end">'</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 1015px;">  <span class="ace_support ace_type">display</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_support ace_constant">block</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 1044px;">  <span class="ace_support ace_type">width</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">35</span><span class="ace_keyword">px</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 1073px;">  <span class="ace_support ace_type">height</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">35</span><span class="ace_keyword">px</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 1102px;">  <span class="ace_support ace_type">position</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_support ace_constant">absolute</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 1131px;">  <span class="ace_support ace_type">left</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">50</span><span class="ace_keyword">%</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 1160px;">  <span class="ace_support ace_type">bottom</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">-65</span><span class="ace_keyword">px</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 1189px;">  <span class="ace_support ace_type">transform</span><span class="ace_punctuation ace_operator">:</span> translate(<span class="ace_constant ace_numeric">-50</span><span class="ace_keyword">%</span>, <span class="ace_constant ace_numeric">-50</span><span class="ace_keyword">%</span>)<span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 1218px;">  <span class="ace_support ace_type">background</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">#333</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 1247px;">  <span class="ace_support ace_type">border-radius</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">50</span><span class="ace_keyword">%</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 1276px;"><span class="ace_paren ace_rparen">}</span></div><div class="ace_line" style="height: 29px; top: 1305px;"></div><div class="ace_line" style="height: 29px; top: 1334px;"><span class="ace_comment">/* The screen (or content) of the device */</span></div><div class="ace_line" style="height: 29px; top: 1363px;"><span class="ace_variable">.smartphone</span> <span class="ace_variable">.content</span> <span class="ace_paren ace_lparen">{</span></div><div class="ace_line" style="height: 29px; top: 1392px;">  <span class="ace_support ace_type">width</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">360</span><span class="ace_keyword">px</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 1421px;">  <span class="ace_support ace_type">height</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_constant ace_numeric">640</span><span class="ace_keyword">px</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 1450px;">  <span class="ace_support ace_type">background</span><span class="ace_punctuation ace_operator">:</span> <span class="ace_support ace_constant ace_color">white</span><span class="ace_punctuation ace_operator">;</span></div><div class="ace_line" style="height: 29px; top: 1479px;"><span class="ace_paren ace_rparen">}</span></div><div class="ace_line" style="height: 29px; top: 1508px;"><span class="ace_meta ace_tag ace_punctuation ace_end-tag-open ace_xml">&lt;/</span><span class="ace_meta ace_tag ace_style ace_tag-name ace_xml">style</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span></div><div class="ace_line" style="height: 29px; top: 1537px;"><span class="ace_meta ace_tag ace_punctuation ace_end-tag-open ace_xml">&lt;/</span><span class="ace_meta ace_tag ace_tag-name ace_xml">head</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span></div><div class="ace_line" style="height: 29px; top: 1566px;"><span class="ace_meta ace_tag ace_punctuation ace_tag-open ace_xml">&lt;</span><span class="ace_meta ace_tag ace_tag-name ace_xml">body</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span></div><div class="ace_line" style="height: 29px; top: 1595px;"></div><div class="ace_line" style="height: 29px; top: 1624px;"><span class="ace_meta ace_tag ace_punctuation ace_tag-open ace_xml">&lt;</span><span class="ace_meta ace_tag ace_tag-name ace_xml">div</span><span class="ace_text ace_tag-whitespace ace_xml"> </span><span class="ace_entity ace_other ace_attribute-name ace_xml">class</span><span class="ace_keyword ace_operator ace_attribute-equals ace_xml">=</span><span class="ace_string ace_attribute-value ace_xml">"smartphone"</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span></div><div class="ace_line" style="height: 29px; top: 1653px;"><span class="ace_text ace_xml">  </span><span class="ace_meta ace_tag ace_punctuation ace_tag-open ace_xml">&lt;</span><span class="ace_meta ace_tag ace_tag-name ace_xml">div</span><span class="ace_text ace_tag-whitespace ace_xml"> </span><span class="ace_entity ace_other ace_attribute-name ace_xml">class</span><span class="ace_keyword ace_operator ace_attribute-equals ace_xml">=</span><span class="ace_string ace_attribute-value ace_xml">"content"</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span></div><div class="ace_line" style="height: 29px; top: 1682px;"><span class="ace_text ace_xml">    </span><span class="ace_meta ace_tag ace_punctuation ace_tag-open ace_xml">&lt;</span><span class="ace_meta ace_tag ace_tag-name ace_xml">h1</span><span class="ace_text ace_tag-whitespace ace_xml"> </span><span class="ace_entity ace_other ace_attribute-name ace_xml">style</span><span class="ace_keyword ace_operator ace_attribute-equals ace_xml">=</span><span class="ace_string ace_attribute-value ace_xml">"text-align:center;color:#123456"</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span><span class="ace_text ace_xml">Made By Hitesh</span><span class="ace_meta ace_tag ace_punctuation ace_end-tag-open ace_xml">&lt;/</span><span class="ace_meta ace_tag ace_tag-name ace_xml">h1</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span></div><div class="ace_line" style="height: 29px; top: 1711px;"><span class="ace_text ace_xml">  </span><span class="ace_meta ace_tag ace_punctuation ace_end-tag-open ace_xml">&lt;/</span><span class="ace_meta ace_tag ace_tag-name ace_xml">div</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span></div><div class="ace_line" style="height: 29px; top: 1740px;"><span class="ace_meta ace_tag ace_punctuation ace_end-tag-open ace_xml">&lt;/</span><span class="ace_meta ace_tag ace_tag-name ace_xml">div</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span></div><div class="ace_line" style="height: 29px; top: 1769px;"></div><div class="ace_line" style="height: 29px; top: 1798px;"><span class="ace_meta ace_tag ace_punctuation ace_end-tag-open ace_xml">&lt;/</span><span class="ace_meta ace_tag ace_tag-name ace_xml">body</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span></div><div class="ace_line" style="height: 29px; top: 1827px;"><span class="ace_meta ace_tag ace_punctuation ace_end-tag-open ace_xml">&lt;/</span><span class="ace_meta ace_tag ace_tag-name ace_xml">html</span><span class="ace_meta ace_tag ace_punctuation ace_tag-close ace_xml">&gt;</span></div></div><div class="ace_layer ace_marker-layer"></div><div class="ace_layer ace_cursor-layer ace_hidden-cursors"><div class="ace_cursor" style="animation-duration: 1000ms; display: block; transform: translate(170px, 203px); width: 13px; height: 29px;"></div></div></div></div><div class="ace_scrollbar ace_scrollbar-v" style="width: 20px; bottom: 0px;"><div class="ace_scrollbar-inner" style="width: 20px; height: 1856px;"></div></div><div class="ace_scrollbar ace_scrollbar-h" style="height: 20px; left: 0px; right: 0px;"><div class="ace_scrollbar-inner" style="height: 20px; width: 878px;"></div></div><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font: inherit; overflow: hidden;"><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font: inherit; overflow: visible;">הההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההההה</div><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font-style: inherit; font-variant: inherit; font-stretch: inherit; font-size: inherit; line-height: inherit; font-family: inherit; overflow: visible;">XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</div></div></div>



  <iframe id="iframe" frameborder="0">

  </iframe>

</div>



	<script>



function update()

{

	var idoc = document.getElementById('iframe').contentWindow.document;



	idoc.open();

	idoc.write(editor.getValue());

	idoc.close();

}



function setupEditor()

{

  window.editor = ace.edit("editor");

  editor.setTheme("ace/theme/monokai");

  editor.getSession().setMode("ace/mode/html");

  editor.setValue(`<!DOCTYPE html>

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
/* The device with borders */
.smartphone {
  position: relative;
  width: 360px;
  height: 640px;
  margin: auto;
  border: 16px black solid;
  border-top-width: 60px;
  border-bottom-width: 60px;
  border-radius: 36px;
}

/* The horizontal line on the top of the device */
.smartphone:before {
  content: '';
  display: block;
  width: 60px;
  height: 5px;
  position: absolute;
  top: -30px;
  left: 50%;
  transform: translate(-50%, -50%);
  background: #333;
  border-radius: 10px;
}

/* The circle on the bottom of the device */
.smartphone:after {
  content: '';
  display: block;
  width: 35px;
  height: 35px;
  position: absolute;
  left: 50%;
  bottom: -65px;
  transform: translate(-50%, -50%);
  background: #333;
  border-radius: 50%;
}

/* The screen (or content) of the device */
.smartphone .content {
  width: 360px;
  height: 640px;
  background: white;
}
</style>
</head>
<body>

<div class="smartphone">
  <div class="content">
    <h1 style="text-align:center;color:#123456">Made By Hitesh</h1>
  </div>
</div>

</body>
</html>`,1); //1 = moves cursor to end



  editor.getSession().on('change', function() {

    update();

  });



  editor.focus();

  

  

  editor.setOptions({

    fontSize: "16pt",

    showLineNumbers: false,

    showGutter: false,

    vScrollBarAlwaysVisible:true,

    enableBasicAutocompletion: false, enableLiveAutocompletion: false

  });



  editor.setShowPrintMargin(false);

  editor.setBehavioursEnabled(false);

}



setupEditor();

update();



		function ready() {

			// body...

			setupEditor();

			update();

		}

	</script>







</body></html>
