# Copyright (C) 2022 The Qt Company Ltd.
# SPDX-License-Identifier: LicenseRef-Qt-Commercial OR GPL-3.0-only WITH Qt-GPL-exception-1.0

qt_internal_add_plugin(QTextToSpeechMockPlugin
    OUTPUT_NAME qtexttospeech_mock
    PLUGIN_TYPE texttospeech
    SOURCES
        qtexttospeech_mock.cpp qtexttospeech_mock.h
        qtexttospeech_mock_plugin.cpp qtexttospeech_mock_plugin.h
    LIBRARIES
        Qt::Core
        Qt::TextToSpeech
)
