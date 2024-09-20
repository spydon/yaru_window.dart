## 0.1.3

- Remove `delete-event` handler in favor of `didRequestAppExit()` (#35)

## [0.3.0](https://github.com/spydon/yaru_window.dart/compare/yaru_window_linux-v0.2.0...yaru_window_linux-v0.3.0) (2024-09-20)


* always call gtk_window_set_title in yaru_window_set_title ([f92fff8](https://github.com/spydon/yaru_window.dart/commit/f92fff8bd32bc7de6dbbf37687ba60f7472dc478))
* **linux:** wire up YaruWindow.onClose with didRequestAppExit() ([#35](https://github.com/spydon/yaru_window.dart/issues/35)) ([df07dc4](https://github.com/spydon/yaru_window.dart/commit/df07dc4b2c4e3f18d5c0daeb339937f2ccfa7097)), closes [#33](https://github.com/spydon/yaru_window.dart/issues/33)

## [0.2.0](https://github.com/ubuntu/yaru_window.dart/compare/yaru_window_linux-v0.1.3...yaru_window_linux-v0.2.0) (2023-12-15)


* always call gtk_window_set_title in yaru_window_set_title ([f92fff8](https://github.com/ubuntu/yaru_window.dart/commit/f92fff8bd32bc7de6dbbf37687ba60f7472dc478))

## 0.1.2

- Migrate to Flutter 3.10 and Dart 3.0.

## 0.1.1

- Emit button release at drag end.

## 0.1.0

- Initial version.
