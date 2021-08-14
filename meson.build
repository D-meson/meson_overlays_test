project(
    'meson_overlays_test',
    ['d'],
    license: 'BSL-1.0',
    meson_version: '>=0.58.1',
)

test_exe = subproject('taggedalgebraic').get_variable('test_exe')

test('test_taggedalgebraic', test_exe)
