# The files DEPS and .DEPS.git need to be manually kept in sync. Depending on
# whether buildtools is used from a svn or git project one or the other is used.

recursion = 1
use_relative_paths = True

vars = {
  "git_url": "https://chromium.googlesource.com",

  "clang_format_rev": "81edd558fea5dd7855d67a1dc61db34ae8c1fd63", # r223685
}

deps = {
  "clang_format/script":
      Var("git_url") + "/chromium/llvm-project/cfe/tools/clang-format.git@" +
      Var("clang_format_rev"),
}
