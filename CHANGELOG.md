##### v0.2.2 (February 04 2018)
 * [Lua, EEL] Updated completions to match REAPER 5.965, SWS 2.10.0, ReaPack 1.2.1 and js_ReaScriptAPI 0.963

##### v0.2.1 (September 29 2018)
 * [Lua] Due to bug in Sublime Text API, when using Lua completions, words in current file weren't auto-completed.
         So instead of working on specific folders, auto complete works on all Lua scripts. If you don't want
         REAPER auto-completions for other Lua scripts, simply disable ReaSyntax while editing those files

##### v0.2.0 (September 29 2018)
 * [Lua] Added Lua completion list. All scripts load it - REAPER or not. This can be limited to specific folders through settings
 * [JS, EEL, WALTER] Updated syntax and completion lists to match REAPER 5.96pre12, SWS 2.9.8 and ReaPack 1.2.1
 * [JS, EEL] Fixed indentation

##### v0.1.1 (October 6 2014)
 * [JS, EEL, WALTER] Fixed toggling comments
 * [EEL] Added SetCursorContext() to completion list

##### v0.1.0 (September 21 2014)
 * [JS, EEL, WALTER] Added auto completion for built-in functions (EEL, JS) and keywords (WALTER)
 * [JS, EEL] Fixed local/global/instance parameters
 * [JS, EEL] Added support for namespace function parameters (a*)
 * [JS] Fixed slider description when using various characters that were not letters
 * [JS] Added support for gfx_ext_retina, import and options:gmem

##### v0.0.1 (June 5 2014)
 * Initial release