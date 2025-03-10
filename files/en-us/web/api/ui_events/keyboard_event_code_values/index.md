---
title: 'Code values for keyboard events'
slug: Web/API/UI_Events/Keyboard_event_code_values
page-type: guide
---

{{DefaultAPISidebar("UI Events")}}

The following tables show what code values are used for each native scancode or virtual keycode on major platforms. The reason is that some browsers choose to interpret physical keys differently, there are some differences in which keys map to which codes. These tables show those variations when known.

## Code values on Windows

This table shows the Windows scan codes representing keys and the `KeyboardEvent.code` values which correspond to those hardware keys. Only keys which generate scan codes on Windows are listed.

In the cells, "(❌ Missing)" means that this code value cannot be detected on this browser;
"(⚠️ Not the same on xyz)" means that this string represents a different code value on the browser xyz and that special care has to be done
when using it.

<table class="standard-table">
  <thead>
    <tr>
      <th scope="row"></th>
      <th colspan="2" scope="col">
        <strong><code>KeyboardEvent.code</code></strong> value
      </th>
    </tr>
    <tr>
      <th scope="row">Code</th>
      <th scope="col">Firefox</th>
      <th scope="col">Chrome</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row"><code>0x0000</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0001</code></th>
      <td><code>"Escape"</code></td>
      <td><code>"Escape"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0002</code></th>
      <td><code>"Digit1"</code></td>
      <td><code>"Digit1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0003</code></th>
      <td><code>"Digit2"</code></td>
      <td><code>"Digit2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0004</code></th>
      <td><code>"Digit3"</code></td>
      <td><code>"Digit3"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0005</code></th>
      <td><code>"Digit4"</code></td>
      <td><code>"Digit4"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0006</code></th>
      <td><code>"Digit5"</code></td>
      <td><code>"Digit5"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0007</code></th>
      <td><code>"Digit6"</code></td>
      <td><code>"Digit6"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0008</code></th>
      <td><code>"Digit7"</code></td>
      <td><code>"Digit7"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0009</code></th>
      <td><code>"Digit8"</code></td>
      <td><code>"Digit8"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000A</code></th>
      <td><code>"Digit9"</code></td>
      <td><code>"Digit9"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000B</code></th>
      <td><code>"Digit0"</code></td>
      <td><code>"Digit0"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000C</code></th>
      <td><code>"Minus"</code></td>
      <td><code>"Minus"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000D</code></th>
      <td><code>"Equal"</code></td>
      <td><code>"Equal"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000E</code></th>
      <td><code>"Backspace"</code></td>
      <td><code>"Backspace"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000F</code></th>
      <td><code>"Tab"</code></td>
      <td><code>"Tab"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0010</code></th>
      <td><code>"KeyQ"</code></td>
      <td><code>"KeyQ"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0011</code></th>
      <td><code>"KeyW"</code></td>
      <td><code>"KeyW"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0012</code></th>
      <td><code>"KeyE"</code></td>
      <td><code>"KeyE"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0013</code></th>
      <td><code>"KeyR"</code></td>
      <td><code>"KeyR"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0014</code></th>
      <td><code>"KeyT"</code></td>
      <td><code>"KeyT"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0015</code></th>
      <td><code>"KeyY"</code></td>
      <td><code>"KeyY"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0016</code></th>
      <td><code>"KeyU"</code></td>
      <td><code>"KeyU"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0017</code></th>
      <td><code>"KeyI"</code></td>
      <td><code>"KeyI"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0018</code></th>
      <td><code>"KeyO"</code></td>
      <td><code>"KeyO"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0019</code></th>
      <td><code>"KeyP"</code></td>
      <td><code>"KeyP"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001A</code></th>
      <td><code>"BracketLeft"</code></td>
      <td><code>"BracketLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001B</code></th>
      <td><code>"BracketRight"</code></td>
      <td><code>"BracketRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001C</code></th>
      <td><code>"Enter"</code></td>
      <td><code>"Enter"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001D</code></th>
      <td><code>"ControlLeft"</code></td>
      <td><code>"ControlLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001E</code></th>
      <td><code>"KeyA"</code></td>
      <td><code>"KeyA"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001F</code></th>
      <td><code>"KeyS"</code></td>
      <td><code>"KeyS"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0020</code></th>
      <td><code>"KeyD"</code></td>
      <td><code>"KeyD"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0021</code></th>
      <td><code>"KeyF"</code></td>
      <td><code>"KeyF"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0022</code></th>
      <td><code>"KeyG"</code></td>
      <td><code>"KeyG"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0023</code></th>
      <td><code>"KeyH"</code></td>
      <td><code>"KeyH"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0024</code></th>
      <td><code>"KeyJ"</code></td>
      <td><code>"KeyJ"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0025</code></th>
      <td><code>"KeyK"</code></td>
      <td><code>"KeyK"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0026</code></th>
      <td><code>"KeyL"</code></td>
      <td><code>"KeyL"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0027</code></th>
      <td><code>"Semicolon"</code></td>
      <td><code>"Semicolon"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0028</code></th>
      <td><code>"Quote"</code></td>
      <td><code>"Quote"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0029</code></th>
      <td><code>"Backquote"</code></td>
      <td><code>"Backquote"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002A</code></th>
      <td><code>"ShiftLeft"</code></td>
      <td><code>"ShiftLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002B</code></th>
      <td><code>"Backslash"</code></td>
      <td><code>"Backslash"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002C</code></th>
      <td><code>"KeyZ"</code></td>
      <td><code>"KeyZ"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002D</code></th>
      <td><code>"KeyX"</code></td>
      <td><code>"KeyX"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002E</code></th>
      <td><code>"KeyC"</code></td>
      <td><code>"KeyC"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002F</code></th>
      <td><code>"KeyV"</code></td>
      <td><code>"KeyV"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0030</code></th>
      <td><code>"KeyB"</code></td>
      <td><code>"KeyB"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0031</code></th>
      <td><code>"KeyN"</code></td>
      <td><code>"KeyN"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0032</code></th>
      <td><code>"KeyM"</code></td>
      <td><code>"KeyM"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0033</code></th>
      <td><code>"Comma"</code></td>
      <td><code>"Comma"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0034</code></th>
      <td><code>"Period"</code></td>
      <td><code>"Period"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0035</code></th>
      <td><code>"Slash"</code></td>
      <td><code>"Slash"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0036</code></th>
      <td><code>"ShiftRight"</code></td>
      <td><code>"ShiftRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0037</code></th>
      <td><code>"NumpadMultiply"</code></td>
      <td><code>"NumpadMultiply"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0038</code></th>
      <td><code>"AltLeft"</code></td>
      <td><code>"AltLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0039</code></th>
      <td><code>"Space"</code></td>
      <td><code>"Space"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003A</code></th>
      <td><code>"CapsLock"</code></td>
      <td><code>"CapsLock"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003B</code></th>
      <td><code>"F1"</code></td>
      <td><code>"F1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003C</code></th>
      <td><code>"F2"</code></td>
      <td><code>"F2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003D</code></th>
      <td><code>"F3"</code></td>
      <td><code>"F3"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003E</code></th>
      <td><code>"F4"</code></td>
      <td><code>"F4"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003F</code></th>
      <td><code>"F5"</code></td>
      <td><code>"F5"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0040</code></th>
      <td><code>"F6"</code></td>
      <td><code>"F6"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0041</code></th>
      <td><code>"F7"</code></td>
      <td><code>"F7"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0042</code></th>
      <td><code>"F8"</code></td>
      <td><code>"F8"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0043</code></th>
      <td><code>"F9"</code></td>
      <td><code>"F9"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0044</code></th>
      <td><code>"F10"</code></td>
      <td><code>"F10"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0045</code></th>
      <td><code>"Pause"</code></td>
      <td><code>"Pause"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0046</code></th>
      <td><code>"ScrollLock"</code></td>
      <td><code>"ScrollLock"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0047</code></th>
      <td><code>"Numpad7"</code></td>
      <td><code>"Numpad7"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0048</code></th>
      <td><code>"Numpad8"</code></td>
      <td><code>"Numpad8"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0049</code></th>
      <td><code>"Numpad9"</code></td>
      <td><code>"Numpad9"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004A</code></th>
      <td><code>"NumpadSubtract"</code></td>
      <td><code>"NumpadSubtract"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004B</code></th>
      <td><code>"Numpad4"</code></td>
      <td><code>"Numpad4"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004C</code></th>
      <td><code>"Numpad5"</code></td>
      <td><code>"Numpad5"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004D</code></th>
      <td><code>"Numpad6"</code></td>
      <td><code>"Numpad6"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004E</code></th>
      <td><code>"NumpadAdd"</code></td>
      <td><code>"NumpadAdd"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004F</code></th>
      <td><code>"Numpad1"</code></td>
      <td><code>"Numpad1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0050</code></th>
      <td><code>"Numpad2"</code></td>
      <td><code>"Numpad2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0051</code></th>
      <td><code>"Numpad3"</code></td>
      <td><code>"Numpad3"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0052</code></th>
      <td><code>"Numpad0"</code></td>
      <td><code>"Numpad0"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0053</code></th>
      <td><code>"NumpadDecimal"</code></td>
      <td><code>"NumpadDecimal"</code></td>
    </tr>
    <tr>
      <th scope="row">
        <code>0x0054 (<kbd>Alt</kbd> + <kbd>PrintScreen</kbd>)</code>
      </th>
      <td><code>"PrintScreen"</code> (⚠️ Not the same on Chrome)</td>
      <td><code>""</code> (❌ Missing)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0055</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0056</code></th>
      <td><code>"IntlBackslash"</code></td>
      <td><code>"IntlBackslash"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0057</code></th>
      <td><code>"F11"</code></td>
      <td><code>"F11"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0058</code></th>
      <td><code>"F12"</code></td>
      <td><code>"F12"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0059</code></th>
      <td><code>"NumpadEqual"</code></td>
      <td><code>"NumpadEqual"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x005A</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x005B</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code> (was <code>"F13"</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x005C</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code> (was <code>"F14"</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x005D</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code> (was <code>"F15"</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x005E</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x005F</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0060</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0061</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0062</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0063</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code> (was <code>"F16"</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0064</code></th>
      <td><code>"F13"</code></td>
      <td><code>"F13"</code> (was <code>"F17"</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0065</code></th>
      <td><code>"F14"</code></td>
      <td><code>"F14"</code> (was <code>"F18"</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0066</code></th>
      <td><code>"F15"</code></td>
      <td><code>"F15"</code> (was <code>"F19"</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0067</code></th>
      <td><code>"F16"</code></td>
      <td><code>"F16"</code> (was <code>"F20"</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0068</code></th>
      <td><code>"F17"</code></td>
      <td><code>"F17"</code> (was <code>"F21"</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0069</code></th>
      <td><code>"F18"</code></td>
      <td><code>"F18"</code> (was <code>"F22"</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x006A</code></th>
      <td><code>"F19"</code></td>
      <td><code>"F19"</code> (was <code>"F23"</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x006B</code></th>
      <td><code>"F20"</code></td>
      <td><code>"F20"</code> (was <code>"F24"</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x006C</code></th>
      <td><code>"F21"</code></td>
      <td><code>"F21"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x006D</code></th>
      <td><code>"F22"</code></td>
      <td><code>"F22"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x006E</code></th>
      <td><code>"F23"</code></td>
      <td><code>"F23"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x006F</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0070</code></th>
      <td><code>"KanaMode"</code></td>
      <td><code>"KanaMode"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row">
        <code>0x0071</code> (<kbd>Hanja</kbd> key without Korean keyboard
        layout)
      </th>
      <td><code>"Lang2"</code></td>
      <td><code>"Lang2"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row">
        <code>0x0072</code> (<kbd>Han/Yeong</kbd> key without Korean keyboard
        layout)
      </th>
      <td><code>"Lang1"</code></td>
      <td><code>"Lang1"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0073</code></th>
      <td><code>"IntlRo"</code></td>
      <td><code>"IntlRo"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0074</code>, <code>0x0075</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0076</code></th>
      <td><code>"F24"</code></td>
      <td><code>"F24"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0077</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"Lang4"</code> (was <code>""</code> prior to Chrome 48) (⚠️ Not the same on Firefox)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0078</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"Lang3"</code> (was <code>""</code> prior to Chrome 48) (⚠️ Not the same on Firefox)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0079</code></th>
      <td><code>"Convert"</code></td>
      <td><code>"Convert"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x007A</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x007B</code></th>
      <td><code>"NonConvert"</code></td>
      <td><code>"NonConvert"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x007C</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x007D</code></th>
      <td><code>"IntlYen"</code></td>
      <td><code>"IntlYen"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x007E</code></th>
      <td><code>"NumpadComma"</code></td>
      <td><code>"NumpadComma"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x007F</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE000</code> ～ <code>0xE007</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE008</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"Undo"</code> (⚠️ Not the same on Firefox)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE009</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE00A</code></th>
      <td><code>""</code> (❌ Missing)</td>
      <td><code>"Paste"</code> (⚠️ Not the same on Firefox)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE00B</code> ～ <code>0xE00F</code></th>
      <td>""</td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE010</code></th>
      <td><code>"MediaTrackPrevious"</code></td>
      <td><code>"MediaTrackPrevious"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE011</code> ～ <code>0xE016</code></th>
      <td><code>""</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE017</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"Cut"</code> (⚠️ Not the same on Firefox)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE018</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"Copy"</code> (⚠️ Not the same on Firefox)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE019</code></th>
      <td><code>"MediaTrackNext"</code></td>
      <td><code>"MediaTrackNext"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE01A, 0xE01B</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE01C</code></th>
      <td><code>"NumpadEnter"</code></td>
      <td><code>"NumpadEnter"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE01D</code></th>
      <td><code>"ControlRight"</code></td>
      <td><code>"ControlRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE01E</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code> (was <code>"LaunchMail"</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE01F</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE020</code></th>
      <td><code>"AudioVolumeMute"</code></td>
      <td><code>"AudioVolumeMute"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE021</code></th>
      <td><code>"LaunchApp2"</code></td>
      <td><code>"LaunchApp2"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE022</code></th>
      <td><code>"MediaPlayPause"</code></td>
      <td><code>"MediaPlayPause"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE023</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE024</code></th>
      <td><code>"MediaStop"</code></td>
      <td><code>"MediaStop"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE025</code> ～ <code>0xE02B</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE02C</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"Eject"</code> (⚠️ Not the same on Firefox)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE02D</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE02E</code></th>
      <td><code>"VolumeDown"</code> (⚠️ Not the same on Chrome)</td>
      <td>
        <code>"AudioVolumeDown"</code> (was <code>"VolumeDown"</code> prior to
        Chrome 52) (⚠️ Not the same on Firefox)
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0xE02F</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE030</code></th>
      <td><code>"VolumeUp"</code> (⚠️ Not the same on Chrome)</td>
      <td>
        <code>"AudioVolumeUp"</code> (was <code>"VolumeUp"</code> prior to Chrome
        52) (⚠️ Not the same on Firefox)
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0xE031</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE032</code></th>
      <td><code>"BrowserHome"</code></td>
      <td><code>"BrowserHome"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE033</code>, <code>0xE034</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE035</code></th>
      <td><code>"NumpadDivide"</code></td>
      <td><code>"NumpadDivide"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE036</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE037</code></th>
      <td><code>"PrintScreen"</code></td>
      <td><code>"PrintScreen"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE038</code></th>
      <td><code>"AltRight"</code></td>
      <td><code>"AltRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE039</code>, <code>0xE03A</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE03B</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"Help"</code> (⚠️ Not the same on Firefox)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE03C</code>～ <code>0xE044</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE045</code></th>
      <td><code>"NumLock"</code></td>
      <td><code>"NumLock"</code></td>
    </tr>
    <tr>
      <th scope="row">
        <code>0xE046</code> (<kbd>Ctrl</kbd> + <kbd>Pause</kbd>)
      </th>
      <td><code>"Pause"</code></td>
      <td><code>"Pause"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE047</code></th>
      <td><code>"Home"</code></td>
      <td><code>"Home"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE048</code></th>
      <td><code>"ArrowUp"</code></td>
      <td><code>"ArrowUp"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE049</code></th>
      <td><code>"PageUp"</code></td>
      <td><code>"PageUp"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE04A</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE04B</code></th>
      <td><code>"ArrowLeft"</code></td>
      <td><code>"ArrowLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE04C</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE04D</code></th>
      <td><code>"ArrowRight"</code></td>
      <td><code>"ArrowRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE04E</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE04F</code></th>
      <td><code>"End"</code></td>
      <td><code>"End"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE050</code></th>
      <td><code>"ArrowDown"</code></td>
      <td><code>"ArrowDown"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE051</code></th>
      <td><code>"PageDown"</code></td>
      <td><code>"PageDown"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE052</code></th>
      <td><code>"Insert"</code></td>
      <td><code>"Insert"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE053</code></th>
      <td><code>"Delete"</code></td>
      <td><code>"Delete"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE054</code> ～ <code>0xE05A</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE05B</code></th>
      <td><code>"OSLeft"</code> (⚠️ Not the same on Chrome)</td>
      <td><code>"MetaLeft"</code> (was <code>"OSLeft"</code> prior to Chrome 52) (⚠️ Not the same on Firefox)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE05C</code></th>
      <td><code>"OSRight"</code> (⚠️ Not the same on Chrome)</td>
      <td><code>"MetaRight"</code> (was <code>"OSRight"</code> prior to Chrome 52) (⚠️ Not the same on Firefox)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE05D</code></th>
      <td><code>"ContextMenu"</code></td>
      <td><code>"ContextMenu"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE05E</code></th>
      <td><code>"Power"</code></td>
      <td><code>"Power"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE05F</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"Sleep"</code> (was <code>""</code> prior to Chrome 48) (⚠️ Not the same on Firefox)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE060</code> ～ <code>0xE062</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
      <tr>
      <th scope="row"><code>0xE063</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"WakeUp"</code> (was <code>""</code> prior to Chrome 48) (⚠️ Not the same on Firefox)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE064</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE065</code></th>
      <td><code>"BrowserSearch"</code></td>
      <td><code>"BrowserSearch"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE066</code></th>
      <td><code>"BrowserFavorites"</code></td>
      <td><code>"BrowserFavorites"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE067</code></th>
      <td><code>"BrowserRefresh"</code></td>
      <td><code>"BrowserRefresh"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE068</code></th>
      <td><code>"BrowserStop"</code></td>
      <td><code>"BrowserStop"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE069</code></th>
      <td><code>"BrowserForward"</code></td>
      <td><code>"BrowserForward"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE06A</code></th>
      <td><code>"BrowserBack"</code></td>
      <td><code>"BrowserBack"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0xE06B</code></th>
      <td><code>"LaunchApp1"</code></td>
      <td><code>"LaunchApp1"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE06C</code></th>
      <td><code>"LaunchMail"</code></td>
      <td><code>"LaunchMail"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE06D</code></th>
      <td><code>"MediaSelect"</code></td>
      <td><code>"MediaSelect"</code> (was <code>""</code> prior to Chrome 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0xE06E ～ 0xE0F0</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row">
        <code>0xE0F1</code> (<kbd>Hanja</kbd> key with Korean keyboard layout)
      </th>
      <td><code>"Lang2"</code> (⚠️ Not the same on Chrome)</td>
      <td><code>""</code> (❌ Missing)</td>
    </tr>
    <tr>
      <th scope="row">
        <code>0xE0F2</code> (<kbd>Han/Yeong</kbd> key with Korean keyboard
        layout)
      </th>
      <td><code>"Lang1"</code> (⚠️ Not the same on Chrome)</td>
      <td><code>""</code> (❌ Missing)</td>
    </tr>
  </tbody>
</table>

## Code values on Mac

On macOS, it's hard to get scancode or something which can distinguish a physical key from a key event. Therefore, Gecko always maps `code` value from the virtual keycode.

In the cells,

- "(❌ Missing)" means that this code value cannot be detected on this browser;
- "(⚠️ Not the same on xyz)" means that this string represents a different code value on the browser xyz and that special care has to be done
  when using it;
- "(⚠️ Same string for `0xab`)" means that you cannot distinguished this key with the one matching `0xab`;
- "(⚠️ No events fired actually)" means that even if technically you have a specific string for this code, no event will be dispatched;

<table class="standard-table">
  <thead>
    <tr>
      <th scope="row">Virtual keycode</th>
      <th scope="col">Gecko</th>
      <th scope="col">Chromium</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row"><code>kVK_ANSI_A (0x00)</code></th>
      <td><code>"KeyA"</code></td>
      <td><code>"KeyA"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_S (0x01)</code></th>
      <td><code>"KeyS"</code></td>
      <td><code>"KeyS"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_D (0x02)</code></th>
      <td><code>"KeyD"</code></td>
      <td><code>"KeyD"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_F (0x03)</code></th>
      <td><code>"KeyF"</code></td>
      <td><code>"KeyF"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_H (0x04)</code></th>
      <td><code>"KeyH"</code></td>
      <td><code>"KeyH"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_G (0x05)</code></th>
      <td><code>"KeyG"</code></td>
      <td><code>"KeyG"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Z (0x06)</code></th>
      <td><code>"KeyZ"</code></td>
      <td><code>"KeyZ"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_X (0x07)</code></th>
      <td><code>"KeyX"</code></td>
      <td><code>"KeyX"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_C (0x08)</code></th>
      <td><code>"KeyC"</code></td>
      <td><code>"KeyC"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_V (0x09)</code></th>
      <td><code>"KeyV"</code></td>
      <td><code>"KeyV"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ISO_Section (0x0A)</code></th>
      <td><code>"IntlBackslash"</code></td>
      <td><code>"IntlBackslash"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_B (0x0B)</code></th>
      <td><code>"KeyB"</code></td>
      <td><code>"KeyB"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Q (0x0C)</code></th>
      <td><code>"KeyQ"</code></td>
      <td><code>"KeyQ"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_W (0x0D)</code></th>
      <td><code>"KeyW"</code></td>
      <td><code>"KeyW"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_E (0x0E)</code></th>
      <td><code>"KeyE"</code></td>
      <td><code>"KeyE"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_R (0x0F)</code></th>
      <td><code>"KeyR"</code></td>
      <td><code>"KeyR"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Y (0x10)</code></th>
      <td><code>"KeyY"</code></td>
      <td><code>"KeyY"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_T (0x11)</code></th>
      <td><code>"KeyT"</code></td>
      <td><code>"KeyT"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_1 (0x12)</code></th>
      <td><code>"Digit1"</code></td>
      <td><code>"Digit1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_2 (0x13)</code></th>
      <td><code>"Digit2"</code></td>
      <td><code>"Digit2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_3 (0x14)</code></th>
      <td><code>"Digit3"</code></td>
      <td><code>"Digit3"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_4 (0x15)</code></th>
      <td><code>"Digit4"</code></td>
      <td><code>"Digit4"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_6 (0x16)</code></th>
      <td><code>"Digit6"</code></td>
      <td><code>"Digit6"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_5 (0x17)</code></th>
      <td><code>"Digit5"</code></td>
      <td><code>"Digit5"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Equal (0x18)</code></th>
      <td><code>"Equal"</code></td>
      <td><code>"Equal"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_9 (0x19)</code></th>
      <td><code>"Digit9"</code></td>
      <td><code>"Digit9"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_7 (0x1A)</code></th>
      <td><code>"Digit7"</code></td>
      <td><code>"Digit7"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Minus (0x1B)</code></th>
      <td><code>"Minus"</code></td>
      <td><code>"Minus"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_8 (0x1C)</code></th>
      <td><code>"Digit8"</code></td>
      <td><code>"Digit8"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_0 (0x1D)</code></th>
      <td><code>"Digit0"</code></td>
      <td><code>"Digit0"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_RightBracket (0x1E)</code></th>
      <td><code>"BracketRight"</code></td>
      <td><code>"BracketRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_O (0x1F)</code></th>
      <td><code>"KeyO"</code></td>
      <td><code>"KeyO"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_U (0x20)</code></th>
      <td><code>"KeyU"</code></td>
      <td><code>"KeyU"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_LeftBracket (0x21)</code></th>
      <td><code>"BracketLeft"</code></td>
      <td><code>"BracketLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_I (0x22)</code></th>
      <td><code>"KeyI"</code></td>
      <td><code>"KeyI"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_P (0x23)</code></th>
      <td><code>"KeyP"</code></td>
      <td><code>"KeyP"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_Return (0x24)</code></th>
      <td><code>"Enter"</code></td>
      <td><code>"Enter"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_L (0x25)</code></th>
      <td><code>"KeyL"</code></td>
      <td><code>"KeyL"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_J (0x26)</code></th>
      <td><code>"KeyJ"</code></td>
      <td><code>"KeyJ"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Quote (0x27)</code></th>
      <td><code>"Quote"</code></td>
      <td><code>"Quote"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_K (0x28)</code></th>
      <td><code>"KeyK"</code></td>
      <td><code>"KeyK"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Semicolon (0x29)</code></th>
      <td><code>"Semicolon"</code></td>
      <td><code>"Semicolon"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Backslash (0x2A)</code></th>
      <td><code>"Backslash"</code></td>
      <td><code>"Backslash"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Comma (0x2B)</code></th>
      <td><code>"Comma"</code></td>
      <td><code>"Comma"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Slash (0x2C)</code></th>
      <td><code>"Slash"</code></td>
      <td><code>"Slash"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_N (0x2D)</code></th>
      <td><code>"KeyN"</code></td>
      <td><code>"KeyN"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_M (0x2E)</code></th>
      <td><code>"KeyM"</code></td>
      <td><code>"KeyM"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Period (0x2F)</code></th>
      <td><code>"Period"</code></td>
      <td><code>"Period"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_Tab (0x30)</code></th>
      <td><code>"Tab"</code></td>
      <td><code>"Tab"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_Space (0x31)</code></th>
      <td><code>"Space"</code></td>
      <td><code>"Space"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Grave (0x32)</code></th>
      <td><code>"Backquote"</code></td>
      <td><code>"Backquote"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_Delete (0x33)</code></th>
      <td><code>"Backspace"</code></td>
      <td><code>"Backspace"</code></td>
    </tr>
    <tr>
      <th scope="row">Enter key on keypad of PowerBook (<code>0x34</code>)</th>
      <td><code>"NumpadEnter"</code>(⚠️ Same string for <code>0x4C</code>) (⚠️ Not the same on Chromium)</td>
      <td><code>""</code> (❌ Missing)</td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_Escape (0x35)</code></th>
      <td><code>"Escape"</code></td>
      <td><code>"Escape"</code></td>
    </tr>
    <tr>
      <th scope="row">right-command key (<code>0x36</code>)</th>
      <td><code>"OSRight"</code> (⚠️ Not the same on Chromium)</td>
      <td><code>"MetaRight"</code> (was <code>"OSRight"</code> prior to Chromium 52) (⚠️ Not the same on Gecko)</td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_Command (0x37)</code></th>
      <td><code>"OSLeft"</code> (⚠️ Not the same on Chromium)</td>
      <td><code>"MetaLeft"</code> (was <code>"OSLeft"</code> prior to Chromium 52) (⚠️ Not the same on Gecko)</td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_Shift (0x38)</code></th>
      <td><code>"ShiftLeft"</code></td>
      <td><code>"ShiftLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_CapsLock (0x39)</code></th>
      <td><code>"CapsLock"</code></td>
      <td><code>"CapsLock"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_Option (0x3A)</code></th>
      <td><code>"AltLeft"</code></td>
      <td><code>"AltLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_Control (0x3B)</code></th>
      <td><code>"ControlLeft"</code></td>
      <td><code>"ControlLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_RightShift (0x3C)</code></th>
      <td><code>"ShiftRight"</code></td>
      <td><code>"ShiftRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_RightOption (0x3D)</code></th>
      <td><code>"AltRight"</code></td>
      <td><code>"AltRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_RightControl (0x3E)</code></th>
      <td><code>"ControlRight"</code></td>
      <td><code>"ControlRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_Function (0x3F)</code></th>
      <td><code>"Fn"</code> (⚠️ No events fired actually)</td>
      <td><code>""</code> (❌ Missing) (⚠️ No events fired actually)</td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F17 (0x40)</code></th>
      <td><code>"F17"</code></td>
      <td><code>"F17"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_KeypadDecimal (0x41)</code></th>
      <td><code>"NumpadDecimal"</code></td>
      <td><code>"NumpadDecimal"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_KeypadMultiply (0x43)</code></th>
      <td><code>"NumpadMultiply"</code></td>
      <td><code>"NumpadMultiply"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_KeypadPlus (0x45)</code></th>
      <td><code>"NumpadAdd"</code></td>
      <td><code>"NumpadAdd"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_KeypadClear (0x47)</code></th>
      <td><code>"NumLock"</code></td>
      <td><code>"NumLock"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_VolumeUp (0x48)</code></th>
      <td><code>"VolumeUp"</code> (⚠️ Not the same on Chromium)</td>
      <td>
        <code>"AudioVolumeUp" </code>(was <code>"VolumeUp"</code> prior to Chromium
        1)  (⚠️ Not the same on Gecko)
      </td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_VolumeDown (0x49)</code></th>
      <td><code>"VolumeDown"</code> (⚠️ Not the same on Chromium)</td>
      <td>
        <code>"AudioVolumeDown"</code> (was <code>"VolumeDown"</code> prior to
        Chromium 52) (⚠️ Not the same on Gecko)
      </td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_Mute (0x4A)</code></th>
      <td><code>"VolumeMute"</code> (⚠️ Not the same on Chromium)</td>
      <td>
        <code>"AudioVolumeMute"</code> (was <code>"VolumeMute"</code> prior to
        Chromium 52) (⚠️ Not the same on Gecko)
      </td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_KeypadDivide (0x4B)</code></th>
      <td><code>"NumpadDivide"</code></td>
      <td><code>"NumpadDivide"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_KeypadEnter (0x4C)</code></th>
      <td><code>"NumpadEnter"</code></td>
      <td><code>"NumpadEnter"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_KeypadMinus (0x4E)</code></th>
      <td><code>"NumpadSubtract"</code></td>
      <td><code>"NumpadSubtract"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F18 (0x4F)</code></th>
      <td><code>"F18"</code></td>
      <td><code>"F18"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F19 (0x50)</code></th>
      <td><code>"F19"</code></td>
      <td><code>"F19"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_KeypadEquals (0x51)</code></th>
      <td><code>"NumpadEqual"</code></td>
      <td><code>"NumpadEqual"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Keypad0 (0x52)</code></th>
      <td><code>"Numpad0"</code></td>
      <td><code>"Numpad0"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Keypad1 (0x53)</code></th>
      <td><code>"Numpad1"</code></td>
      <td><code>"Numpad1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Keypad2 (0x54)</code></th>
      <td><code>"Numpad2"</code></td>
      <td><code>"Numpad2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Keypad3 (0x55)</code></th>
      <td><code>"Numpad3"</code></td>
      <td><code>"Numpad3"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Keypad4 (0x56)</code></th>
      <td><code>"Numpad4"</code></td>
      <td><code>"Numpad4"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Keypad5 (0x57)</code></th>
      <td><code>"Numpad5"</code></td>
      <td><code>"Numpad5"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Keypad6 (0x58)</code></th>
      <td><code>"Numpad6"</code></td>
      <td><code>"Numpad6"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Keypad7 (0x59)</code></th>
      <td><code>"Numpad7"</code></td>
      <td><code>"Numpad7"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F20 (0x5A)</code></th>
      <td><code>"F20"</code></td>
      <td><code>"F20"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Keypad8 (0x5B)</code></th>
      <td><code>"Numpad8"</code></td>
      <td><code>"Numpad8"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ANSI_Keypad9 (0x5C)</code></th>
      <td><code>"Numpad9"</code></td>
      <td><code>"Numpad9"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_JIS_Yen (0x5D)</code></th>
      <td><code>"IntlYen"</code></td>
      <td><code>"IntlYen"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_JIS_Underscore (0x5E)</code></th>
      <td><code>"IntlRo"</code></td>
      <td><code>"IntlRo"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_JIS_KeypadComma (0x5F)</code></th>
      <td><code>"NumpadComma"</code></td>
      <td><code>"NumpadComma"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F5 (0x60)</code></th>
      <td><code>"F5"</code></td>
      <td><code>"F5"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F6 (0x61)</code></th>
      <td><code>"F6"</code></td>
      <td><code>"F6"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F7 (0x62)</code></th>
      <td><code>"F7"</code></td>
      <td><code>"F7"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F3 (0x63)</code></th>
      <td><code>"F3"</code></td>
      <td><code>"F3"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F8 (0x64)</code></th>
      <td><code>"F8"</code></td>
      <td><code>"F8"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F9 (0x65)</code></th>
      <td><code>"F9"</code></td>
      <td><code>"F9"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_JIS_Eisu (0x66)</code></th>
      <td><code>"Lang2"</code></td>
      <td><code>"Lang2"</code> (was <code>""</code> prior to Chromium 82) (⚠️ No events fired actually)</td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F11 (0x67)</code></th>
      <td><code>"F11"</code></td>
      <td><code>"F11"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_JIS_Kana (0x68)</code></th>
      <td><code>"Lang1"</code></td>
      <td><code>"Lang1"</code> (was <code>"KanaMode"</code> prior to Chromium 82) (⚠️ No events fired actually)</td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F13 (0x69)</code></th>
      <td><code>"F13"</code></td>
      <td><code>"F13"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F16 (0x6A)</code></th>
      <td><code>"F16"</code></td>
      <td><code>"F16"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F14 (0x6B)</code></th>
      <td><code>"F14"</code></td>
      <td><code>"F14"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F10 (0x6D)</code></th>
      <td><code>"F10"</code></td>
      <td><code>"F10"</code></td>
    </tr>
    <tr>
      <th scope="row">context menu key (<code>0x6E</code>)</th>
      <td><code>"ContextMenu"</code></td>
      <td><code>"ContextMenu"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F12 (0x6F)</code></th>
      <td><code>"F12"</code></td>
      <td><code>"F12"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F15 (0x71)</code></th>
      <td><code>"F15"</code></td>
      <td><code>"F15"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_Help (0x72)</code></th>
      <td><code>"Help"</code> (⚠️ Not the same on Chromium)</td>
      <td><code>"Insert"</code> (⚠️ Not the same on Gecko)</td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_Home (0x73)</code></th>
      <td><code>"Home"</code></td>
      <td><code>"Home"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_PageUp (0x74)</code></th>
      <td><code>"PageUp"</code></td>
      <td><code>"PageUp"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_ForwardDelete (0x75)</code></th>
      <td><code>"Delete"</code></td>
      <td><code>"Delete"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F4 (0x76)</code></th>
      <td><code>"F4"</code></td>
      <td><code>"F4"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_End (0x77)</code></th>
      <td><code>"End"</code></td>
      <td><code>"End"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F2 (0x78)</code></th>
      <td><code>"F2"</code></td>
      <td><code>"F2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_PageDown (0x79)</code></th>
      <td><code>"PageDown"</code></td>
      <td><code>"PageDown"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_F1 (0x7A)</code></th>
      <td><code>"F1"</code></td>
      <td><code>"F1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_LeftArrow (0x7B)</code></th>
      <td><code>"ArrowLeft"</code></td>
      <td><code>"ArrowLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_RightArrow (0x7C)</code></th>
      <td><code>"ArrowRight"</code></td>
      <td><code>"ArrowRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_DownArrow (0x7D)</code></th>
      <td><code>"ArrowDown"</code></td>
      <td><code>"ArrowDown"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>kVK_UpArrow (0x7E)</code></th>
      <td><code>"ArrowUp"</code></td>
      <td><code>"ArrowUp"</code></td>
    </tr>
  </tbody>
</table>

## Code values on Linux (X11)

Note that X has too many keys and some of them are not testable with usual keyboard. So, following table is created from source code which maps from scancode to code value.

In the cells, "(❌ Missing)" means that this code value cannot be detected on this browser.

<table class="standard-table">
  <thead>
    <tr>
      <th scope="row">scancode (hardware_keycode)</th>
      <th scope="col">Gecko</th>
      <th scope="col">Chromium</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row"><code>0x0009</code></th>
      <td><code>"Escape"</code></td>
      <td><code>"Escape"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000A</code></th>
      <td><code>"Digit1"</code></td>
      <td><code>"Digit1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000B</code></th>
      <td><code>"Digit2"</code></td>
      <td><code>"Digit2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000C</code></th>
      <td><code>"Digit3"</code></td>
      <td><code>"Digit3"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000D</code></th>
      <td><code>"Digit4"</code></td>
      <td><code>"Digit4"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000E</code></th>
      <td><code>"Digit5"</code></td>
      <td><code>"Digit5"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000F</code></th>
      <td><code>"Digit6"</code></td>
      <td><code>"Digit6"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0010</code></th>
      <td><code>"Digit7"</code></td>
      <td><code>"Digit7"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0011</code></th>
      <td><code>"Digit8"</code></td>
      <td><code>"Digit8"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0012</code></th>
      <td><code>"Digit9"</code></td>
      <td><code>"Digit9"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0013</code></th>
      <td><code>"Digit0"</code></td>
      <td><code>"Digit0"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0014</code></th>
      <td><code>"Minus"</code></td>
      <td><code>"Minus"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0015</code></th>
      <td><code>"Equal"</code></td>
      <td><code>"Equal"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0016</code></th>
      <td><code>"Backspace"</code></td>
      <td><code>"Backspace"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0017</code></th>
      <td><code>"Tab"</code></td>
      <td><code>"Tab"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0018</code></th>
      <td><code>"KeyQ"</code></td>
      <td><code>"KeyQ"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0019</code></th>
      <td><code>"KeyW"</code></td>
      <td><code>"KeyW"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001A</code></th>
      <td><code>"KeyE"</code></td>
      <td><code>"KeyE"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001B</code></th>
      <td><code>"KeyR"</code></td>
      <td><code>"KeyR"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001C</code></th>
      <td><code>"KeyT"</code></td>
      <td><code>"KeyT"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001D</code></th>
      <td><code>"KeyY"</code></td>
      <td><code>"KeyY"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001E</code></th>
      <td><code>"KeyU"</code></td>
      <td><code>"KeyU"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001F</code></th>
      <td><code>"KeyI"</code></td>
      <td><code>"KeyI"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0020</code></th>
      <td><code>"KeyO"</code></td>
      <td><code>"KeyO"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0021</code></th>
      <td><code>"KeyP"</code></td>
      <td><code>"KeyP"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0022</code></th>
      <td><code>"BracketLeft"</code></td>
      <td><code>"BracketLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0023</code></th>
      <td><code>"BracketRight"</code></td>
      <td><code>"BracketRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0024</code></th>
      <td><code>"Enter"</code></td>
      <td><code>"Enter"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0025</code></th>
      <td><code>"ControlLeft"</code></td>
      <td><code>"ControlLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0026</code></th>
      <td><code>"KeyA"</code></td>
      <td><code>"KeyA"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0027</code></th>
      <td><code>"KeyS"</code></td>
      <td><code>"KeyS"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0028</code></th>
      <td><code>"KeyD"</code></td>
      <td><code>"KeyD"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0029</code></th>
      <td><code>"KeyF"</code></td>
      <td><code>"KeyF"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002A</code></th>
      <td><code>"KeyG"</code></td>
      <td><code>"KeyG"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002B</code></th>
      <td><code>"KeyH"</code></td>
      <td><code>"KeyH"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002C</code></th>
      <td><code>"KeyJ"</code></td>
      <td><code>"KeyJ"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002D</code></th>
      <td><code>"KeyK"</code></td>
      <td><code>"KeyK"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002E</code></th>
      <td><code>"KeyL"</code></td>
      <td><code>"KeyL"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002F</code></th>
      <td><code>"Semicolon"</code></td>
      <td><code>"Semicolon"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0030</code></th>
      <td><code>"Quote"</code></td>
      <td><code>"Quote"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0031</code></th>
      <td><code>"Backquote"</code></td>
      <td><code>"Backquote"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0032</code></th>
      <td><code>"ShiftLeft"</code></td>
      <td><code>"ShiftLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0033</code></th>
      <td><code>"Backslash"</code></td>
      <td><code>"Backslash"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0034</code></th>
      <td><code>"KeyZ"</code></td>
      <td><code>"KeyZ"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0035</code></th>
      <td><code>"KeyX"</code></td>
      <td><code>"KeyX"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0036</code></th>
      <td><code>"KeyC"</code></td>
      <td><code>"KeyC"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0037</code></th>
      <td><code>"KeyV"</code></td>
      <td><code>"KeyV"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0038</code></th>
      <td><code>"KeyB"</code></td>
      <td><code>"KeyB"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0039</code></th>
      <td><code>"KeyN"</code></td>
      <td><code>"KeyN"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003A</code></th>
      <td><code>"KeyM"</code></td>
      <td><code>"KeyM"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003B</code></th>
      <td><code>"Comma"</code></td>
      <td><code>"Comma"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003C</code></th>
      <td><code>"Period"</code></td>
      <td><code>"Period"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003D</code></th>
      <td><code>"Slash"</code></td>
      <td><code>"Slash"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003E</code></th>
      <td><code>"ShiftRight"</code></td>
      <td><code>"ShiftRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003F</code></th>
      <td><code>"NumpadMultiply"</code></td>
      <td><code>"NumpadMultiply"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0040</code></th>
      <td><code>"AltLeft"</code></td>
      <td><code>"AltLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0041</code></th>
      <td><code>"Space"</code></td>
      <td><code>"Space"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0042</code></th>
      <td><code>"CapsLock"</code></td>
      <td><code>"CapsLock"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0043</code></th>
      <td><code>"F1"</code></td>
      <td><code>"F1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0044</code></th>
      <td><code>"F2"</code></td>
      <td><code>"F2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0045</code></th>
      <td><code>"F3"</code></td>
      <td><code>"F3"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0046</code></th>
      <td><code>"F4"</code></td>
      <td><code>"F4"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0047</code></th>
      <td><code>"F5"</code></td>
      <td><code>"F5"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0048</code></th>
      <td><code>"F6"</code></td>
      <td><code>"F6"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0049</code></th>
      <td><code>"F7"</code></td>
      <td><code>"F7"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004A</code></th>
      <td><code>"F8"</code></td>
      <td><code>"F8"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004B</code></th>
      <td><code>"F9"</code></td>
      <td><code>"F9"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004C</code></th>
      <td><code>"F10"</code></td>
      <td><code>"F10"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004D</code></th>
      <td><code>"NumLock"</code></td>
      <td><code>"NumLock"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004E</code></th>
      <td><code>"ScrollLock"</code></td>
      <td><code>"ScrollLock"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004F</code></th>
      <td><code>"Numpad7"</code></td>
      <td><code>"Numpad7"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0050</code></th>
      <td><code>"Numpad8"</code></td>
      <td><code>"Numpad8"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0051</code></th>
      <td><code>"Numpad9"</code></td>
      <td><code>"Numpad9"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0052</code></th>
      <td><code>"NumpadSubtract"</code></td>
      <td><code>"NumpadSubtract"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0053</code></th>
      <td><code>"Numpad4"</code></td>
      <td><code>"Numpad4"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0054</code></th>
      <td><code>"Numpad5"</code></td>
      <td><code>"Numpad5"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0055</code></th>
      <td><code>"Numpad6"</code></td>
      <td><code>"Numpad6"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0056</code></th>
      <td><code>"NumpadAdd"</code></td>
      <td><code>"NumpadAdd"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0057</code></th>
      <td><code>"Numpad1"</code></td>
      <td><code>"Numpad1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0058</code></th>
      <td><code>"Numpad2"</code></td>
      <td><code>"Numpad2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0059</code></th>
      <td><code>"Numpad3"</code></td>
      <td><code>"Numpad3"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x005A</code></th>
      <td><code>"Numpad0"</code></td>
      <td><code>"Numpad0"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x005B</code></th>
      <td><code>"NumpadDecimal"</code></td>
      <td><code>"NumpadDecimal"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x005C</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x005D</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"Lang5"</code> (was <code>""</code> prior to Chromium 48) (⚠️ Not the same on Gecko)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x005E</code></th>
      <td><code>"IntlBackslash"</code></td>
      <td><code>"IntlBackslash"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x005F</code></th>
      <td><code>"F11"</code></td>
      <td><code>"F11"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0060</code></th>
      <td><code>"F12"</code></td>
      <td><code>"F12"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0061</code></th>
      <td><code>"IntlRo"</code></td>
      <td><code>"IntlRo"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0062</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"Lang3"</code> (⚠️ Not the same on Gecko)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0063</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"Lang4"</code> (⚠️ Not the same on Gecko)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0064</code></th>
      <td><code>"Convert"</code></td>
      <td><code>"Convert"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0065</code></th>
      <td><code>"KanaMode"</code></td>
      <td><code>"KanaMode"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0066</code></th>
      <td><code>"NonConvert"</code></td>
      <td><code>"NonConvert"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0067</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0068</code></th>
      <td><code>"NumpadEnter"</code></td>
      <td><code>"NumpadEnter"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0069</code></th>
      <td><code>"ControlRight"</code></td>
      <td><code>"ControlRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x006A</code></th>
      <td><code>"NumpadDivide"</code></td>
      <td><code>"NumpadDivide"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x006B</code></th>
      <td><code>"PrintScreen"</code></td>
      <td><code>"PrintScreen"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x006C</code></th>
      <td><code>"AltRight"</code></td>
      <td><code>"AltRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x006D</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x006E</code></th>
      <td><code>"Home"</code></td>
      <td><code>"Home"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x006F</code></th>
      <td><code>"ArrowUp"</code></td>
      <td><code>"ArrowUp"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0070</code></th>
      <td><code>"PageUp"</code></td>
      <td><code>"PageUp"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0071</code></th>
      <td><code>"ArrowLeft"</code></td>
      <td><code>"ArrowLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0072</code></th>
      <td><code>"ArrowRight"</code></td>
      <td><code>"ArrowRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0073</code></th>
      <td><code>"End"</code></td>
      <td><code>"End"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0074</code></th>
      <td><code>"ArrowDown"</code></td>
      <td><code>"ArrowDown"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0075</code></th>
      <td><code>"PageDown"</code></td>
      <td><code>"PageDown"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0076</code></th>
      <td><code>"Insert"</code></td>
      <td><code>"Insert"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0077</code></th>
      <td><code>"Delete"</code></td>
      <td><code>"Delete"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0078</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0079</code></th>
      <td><code>"VolumeMute"</code> (⚠️ Not the same on Chromium)</td>
      <td>
        <code>"AudioVolumeMute"</code> (was <code>"VolumeMute"</code> prior to
        Chromium 52) (⚠️ Not the same on Gecko)
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x007A</code></th>
      <td><code>"VolumeDown"</code> (⚠️ Not the same on Chromium)</td>
      <td>
        <code>"AudioVolumeDown"</code> (was <code>"VolumeDown"</code> prior to
        Chromium 52) (⚠️ Not the same on Gecko)
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x007B</code></th>
      <td><code>"VolumeUp"</code> (⚠️ Not the same on Chromium)</td>
      <td>
        <code>"AudioVolumeUp"</code> (was <code>"VolumeUp"</code> prior to Chromium
        52) (⚠️ Not the same on Gecko)
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x007C</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"Power"</code> (⚠️ Not the same on Gecko)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x007D</code></th>
      <td><code>"NumpadEqual"</code></td>
      <td><code>"NumpadEqual"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x007E</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x007F</code></th>
      <td><code>"Pause"</code></td>
      <td><code>"Pause"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0080</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0081</code></th>
      <td><code>"NumpadComma"</code></td>
      <td><code>"NumpadComma"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0082</code></th>
      <td><code>"Lang1"</code></td>
      <td><code>"Lang1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0083</code></th>
      <td><code>"Lang2"</code></td>
      <td><code>"Lang2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0084</code></th>
      <td><code>"IntlYen"</code></td>
      <td><code>"IntlYen"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0085</code></th>
      <td><code>"OSLeft"</code> (⚠️ Not the same on Chromium)</td>
      <td><code>"MetaLeft"</code> (was <code>"OSLeft"</code> prior to Chromium 52) (⚠️ Not the same on Gecko)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0086</code></th>
      <td><code>"OSRight"</code> (⚠️ Not the same on Chromium)</td>
      <td><code>"MetaRight"</code> (was <code>"OSRight"</code> prior to Chromium 52) (⚠️ Not the same on Gecko)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0087</code></th>
      <td><code>"ContextMenu"</code></td>
      <td><code>"ContextMenu"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0088</code></th>
      <td><code>"BrowserStop"</code></td>
      <td><code>"BrowserStop"</code> (was <code>"Abort"</code> prior to Chromium 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0089</code></th>
      <td><code>"Again"</code></td>
      <td><code>"Again"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x008A</code></th>
      <td><code>"Props"</code> (⚠️ Not the same on Chromium)</td>
      <td><code>""</code> (❌ Missing)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x008B</code></th>
      <td><code>"Undo"</code></td>
      <td><code>"Undo"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x008C</code></th>
      <td><code>"Select"</code></td>
      <td><code>"Select"</code> (was <code>""</code> prior to Chromium 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x008D</code></th>
      <td><code>"Copy"</code></td>
      <td><code>"Copy"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x008E</code></th>
      <td><code>"Open"</code></td>
      <td><code>"Open"</code> (was <code>""</code> prior to Chromium 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x008F</code></th>
      <td><code>"Paste"</code></td>
      <td><code>"Paste"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0090</code></th>
      <td><code>"Find"</code></td>
      <td><code>"Find"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0091</code></th>
      <td><code>"Cut"</code></td>
      <td><code>"Cut"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0092</code></th>
      <td><code>"Help"</code></td>
      <td><code>"Help"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0093</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0094</code></th>
      <td><code>"LaunchApp2"</code></td>
      <td><code>"LaunchApp2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0095</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0096</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"Sleep"</code> (⚠️ Not the same on Gecko)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0097</code></th>
      <td><code>"WakeUp"</code></td>
      <td><code>"WakeUp"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0098</code></th>
      <td><code>"LaunchApp1"</code></td>
      <td><code>"LaunchApp1"</code> (was <code>""</code> prior to Chromium 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0099</code> ～ <code>0x00A2</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A3</code></th>
      <td><code>"LaunchMail"</code></td>
      <td><code>"LaunchMail"</code> (was <code>""</code> prior to Chromium 51)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A4</code></th>
      <td><code>"BrowserFavorites"</code></td>
      <td><code>"BrowserFavorites"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A5</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A6</code></th>
      <td><code>"BrowserBack"</code></td>
      <td><code>"BrowserBack"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A7</code></th>
      <td><code>"BrowserForward"</code></td>
      <td><code>"BrowserForward"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A8</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A9</code></th>
      <td><code>"Eject"</code></td>
      <td><code>"Eject"</code> (was <code>""</code> prior to Chromium 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x00AA</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00AB</code></th>
      <td><code>"MediaTrackNext"</code></td>
      <td><code>"MediaTrackNext"</code> (was <code>""</code> prior to Chromium 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x00AC</code></th>
      <td><code>"MediaPlayPause"</code></td>
      <td><code>"MediaPlayPause"</code> (was <code>""</code> prior to Chromium 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x00AD</code></th>
      <td><code>"MediaTrackPrevious"</code></td>
      <td><code>"MediaTrackPrevious"</code> (was <code>""</code> prior to Chromium 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x00AE</code></th>
      <td><code>"MediaStop"</code></td>
      <td><code>"MediaStop"</code> (was <code>""</code> prior to Chromium 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x00AF</code> ～ <code>0x00B2</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00B3</code></th>
      <td><code>"MediaSelect"</code></td>
      <td><code>"MediaSelect"</code> (was <code>""</code> prior to Chromium 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x00B4</code></th>
      <td><code>"BrowserHome"</code></td>
      <td><code>"BrowserHome"</code> (was <code>""</code> prior to Chromium 48)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x00B5</code></th>
      <td><code>"BrowserRefresh"</code></td>
      <td><code>"BrowserRefresh"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00B6</code> ～ <code>0x00BA</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00BB</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"NumpadParenLeft"</code> (⚠️ Not the same on Gecko)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x00BC</code></th>
      <td><code>"Unidentified"</code> (❌ Missing)</td>
      <td><code>"NumpadParenRight"</code> (⚠️ Not the same on Gecko)</td>
    </tr>
    <tr>
      <th scope="row"><code>0x00BD</code>, <code>0x00BE</code></th>
      <td><code>"Unidentified"</code></td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00BF</code></th>
      <td><code>"F13"</code></td>
      <td><code>"F13"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00C0</code></th>
      <td><code>"F14"</code></td>
      <td><code>"F14"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00C1</code></th>
      <td><code>"F15"</code></td>
      <td><code>"F15"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00C2</code></th>
      <td><code>"F16"</code></td>
      <td><code>"F16"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00C3</code></th>
      <td><code>"F17"</code></td>
      <td><code>"F17"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00C4</code></th>
      <td><code>"F18"</code></td>
      <td><code>"F18"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00C5</code></th>
      <td><code>"F19"</code></td>
      <td><code>"F19"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00C6</code></th>
      <td><code>"F20"</code></td>
      <td><code>"F20"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00C7</code></th>
      <td><code>"F21"</code></td>
      <td><code>"F21"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00C8</code></th>
      <td><code>"F22"</code></td>
      <td><code>"F22"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00C9</code></th>
      <td><code>"F23"</code></td>
      <td><code>"F23"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00CA</code></th>
      <td><code>"F24"</code></td>
      <td><code>"F24"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00CB ～ 0x00E0</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
      <td><code>""</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00E1</code></th>
      <td><code>"BrowserSearch"</code> (⚠️ Not the same on Chromium)</td>
      <td><code>"BrowserSearch"</code> (was <code>"BrightnessUp"</code> prior to Chromium 48)</td>
    </tr>
  </tbody>
</table>

## Code values on Firefox for Android

<table class="standard-table">
  <thead>
    <tr>
      <th scope="row">scancode</th>
      <th scope="col">Gecko</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row"><code>0x0001</code></th>
      <td><code>"Escape"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0002</code></th>
      <td><code>"Digit1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0003</code></th>
      <td><code>"Digit2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0004</code></th>
      <td><code>"Digit3"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0005</code></th>
      <td><code>"Digit4"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0006</code></th>
      <td><code>"Digit5"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0007</code></th>
      <td><code>"Digit6"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0008</code></th>
      <td><code>"Digit7"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0009</code></th>
      <td><code>"Digit8"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000A</code></th>
      <td><code>"Digit9"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000B</code></th>
      <td><code>"Digit0"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000C</code></th>
      <td><code>"Minus"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000D</code></th>
      <td><code>"Equal"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000E</code></th>
      <td><code>"Backspace"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x000F</code></th>
      <td><code>"Tab"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0010</code></th>
      <td><code>"KeyQ"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0011</code></th>
      <td><code>"KeyW"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0012</code></th>
      <td><code>"KeyE"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0013</code></th>
      <td><code>"KeyR"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0014</code></th>
      <td><code>"KeyT"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0015</code></th>
      <td><code>"KeyY"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0016</code></th>
      <td><code>"KeyU"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0017</code></th>
      <td><code>"KeyI"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0018</code></th>
      <td><code>"KeyO"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0019</code></th>
      <td><code>"KeyP"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001A</code></th>
      <td><code>"BracketLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001B</code></th>
      <td><code>"BracketRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001C</code></th>
      <td><code>"Enter"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001D</code></th>
      <td><code>"ControlLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001E</code></th>
      <td><code>"KeyA"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x001F</code></th>
      <td><code>"KeyS"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0020</code></th>
      <td><code>"KeyD"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0021</code></th>
      <td><code>"KeyF"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0022</code></th>
      <td><code>"KeyG"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0023</code></th>
      <td><code>"KeyH"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0024</code></th>
      <td><code>"KeyJ"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0025</code></th>
      <td><code>"KeyK"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0026</code></th>
      <td><code>"KeyL"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0027</code></th>
      <td><code>"Semicolon"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0028</code></th>
      <td><code>"Quote"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0029</code></th>
      <td><code>"Backquote"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002A</code></th>
      <td><code>"ShiftLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002B</code></th>
      <td><code>"Backslash"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002C</code></th>
      <td><code>"KeyZ"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002D</code></th>
      <td><code>"KeyX"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002E</code></th>
      <td><code>"KeyC"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x002F</code></th>
      <td><code>"KeyV"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0030</code></th>
      <td><code>"KeyB"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0031</code></th>
      <td><code>"KeyN"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0032</code></th>
      <td><code>"KeyM"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0033</code></th>
      <td><code>"Comma"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0034</code></th>
      <td><code>"Period"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0035</code></th>
      <td><code>"Slash"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0036</code></th>
      <td><code>"ShiftRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0037</code></th>
      <td><code>"NumpadMultiply"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0038</code></th>
      <td><code>"AltLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0039</code></th>
      <td><code>"Space"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003A</code></th>
      <td><code>"CapsLock"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003B</code></th>
      <td><code>"F1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003C</code></th>
      <td><code>"F2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003D</code></th>
      <td><code>"F3"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003E</code></th>
      <td><code>"F4"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x003F</code></th>
      <td><code>"F5"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0040</code></th>
      <td><code>"F6"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0041</code></th>
      <td><code>"F7"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0042</code></th>
      <td><code>"F8"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0043</code></th>
      <td><code>"F9"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0044</code></th>
      <td><code>"F10"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0045</code></th>
      <td><code>"NumLock"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0046</code></th>
      <td><code>"ScrollLock"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0047</code></th>
      <td><code>"Numpad7"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0048</code></th>
      <td><code>"Numpad8"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0049</code></th>
      <td><code>"Numpad9"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004A</code></th>
      <td><code>"NumpadSubtract"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004B</code></th>
      <td><code>"Numpad4"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004C</code></th>
      <td><code>"Numpad5"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004D</code></th>
      <td><code>"Numpad6"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004E</code></th>
      <td><code>"NumpadAdd"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x004F</code></th>
      <td><code>"Numpad1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0050</code></th>
      <td><code>"Numpad2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0051</code></th>
      <td><code>"Numpad3"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0052</code></th>
      <td><code>"Numpad0"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0053</code></th>
      <td><code>"NumpadDecimal"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0054</code>, <code>0x0055</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x0056</code></th>
      <td><code>"IntlBackslash"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0057</code></th>
      <td><code>"F11"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0058</code></th>
      <td><code>"F12"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0059</code></th>
      <td><code>"IntlRo"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x005A</code>, <code>0x005B</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x005C</code></th>
      <td><code>"Convert"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x005D</code></th>
      <td><code>"KanaMode"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x005E</code></th>
      <td><code>"NonConvert"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x005F</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x0060</code></th>
      <td><code>"NumpadEnter"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0061</code></th>
      <td><code>"ControlRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0062</code></th>
      <td><code>"NumpadDivide"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0063</code></th>
      <td><code>"PrintScreen"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0064</code></th>
      <td><code>"AltRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0065</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x0066</code></th>
      <td><code>"Home"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0067</code></th>
      <td><code>"ArrowUp"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0068</code></th>
      <td><code>"PageUp"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0069</code></th>
      <td><code>"ArrowLeft"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x006A</code></th>
      <td><code>"ArrowRight"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x006B</code></th>
      <td><code>"End"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x006C</code></th>
      <td><code>"ArrowDown"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x006D</code></th>
      <td><code>"PageDown"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x006E</code></th>
      <td><code>"Insert"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x006F</code></th>
      <td><code>"Delete"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0070</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x0071</code></th>
      <td>
        <p><code>"VolumeMute"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x0072</code></th>
      <td>
        <p><code>"VolumeDown"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x0073</code></th>
      <td>
        <p><code>"VolumeUp"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x0074</code></th>
      <td><code>"Power"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0075</code></th>
      <td><code>"NumpadEqual"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0076</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x0077</code></th>
      <td><code>"Pause"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0078</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x0079</code></th>
      <td><code>"NumpadComma"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x007A</code></th>
      <td><code>"Lang1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x007B</code></th>
      <td><code>"Lang2"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x007C</code></th>
      <td><code>"IntlYen"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x007D</code></th>
      <td>
        <p><code>"OSLeft"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x007E</code></th>
      <td>
        <p><code>"OSRight"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x007F</code></th>
      <td><code>"ContextMenu"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0080</code></th>
      <td><code>"BrowserStop"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0081</code></th>
      <td>"Again"</td>
    </tr>
    <tr>
      <th scope="row"><code>0x0082</code></th>
      <td><code>"Props"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0083</code></th>
      <td><code>"Undo"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0084</code></th>
      <td><code>"Select"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0085</code></th>
      <td><code>"Copy"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0086</code></th>
      <td><code>"Open"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0087</code></th>
      <td><code>"Paste"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0088</code></th>
      <td><code>"Find"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0089</code></th>
      <td><code>"Cut"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x008A</code></th>
      <td><code>"Help"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x008B</code> ～ <code>0x008D</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x008E</code></th>
      <td><code>"Sleep"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x008F</code></th>
      <td><code>"WakeUp"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0090</code></th>
      <td><code>"LaunchApp1"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x0091</code> ～ <code>0x009B</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x009C</code></th>
      <td><code>"BrowserFavorites"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x009D</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x009E</code></th>
      <td><code>"BrowserBack"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x009F</code></th>
      <td><code>"BrowserForward"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A0</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A1</code></th>
      <td><code>"Eject"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A2</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A3</code></th>
      <td><code>"MediaTrackNext"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A4</code></th>
      <td><code>"MediaPlayPause"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A5</code></th>
      <td><code>"MediaTrackPrevious"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A6</code></th>
      <td><code>"MediaStop"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00A7</code> ～ <code>0x00AC</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x00AD</code></th>
      <td><code>"BrowserRefresh"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00AE</code> ～ <code>0x00B6</code></th>
      <td>"Unidentified"</td>
    </tr>
    <tr>
      <th scope="row"><code>0x00B7</code></th>
      <td><code>"F13"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00B8</code></th>
      <td><code>"F14"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00B9</code></th>
      <td><code>"F15"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00BA</code></th>
      <td><code>"F16"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00BB</code></th>
      <td><code>"F17"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00BC</code></th>
      <td><code>"F18"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00BD</code></th>
      <td><code>"F19"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00BE</code></th>
      <td><code>"F20"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00BF</code></th>
      <td><code>"F21"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00C0</code></th>
      <td><code>"F22"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00C1</code></th>
      <td><code>"F23"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00C2</code></th>
      <td><code>"F24"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00C3</code> ～ <code>0x00D8</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x00D9</code></th>
      <td><code>"BrowserSearch"</code></td>
    </tr>
    <tr>
      <th scope="row"><code>0x00DA</code> ～ <code>0x01CF</code></th>
      <td>
        <p><code>"Unidentified"</code></p>
      </td>
    </tr>
    <tr>
      <th scope="row"><code>0x01D0</code></th>
      <td><code>"Fn"</code></td>
    </tr>
  </tbody>
</table>
