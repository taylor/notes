# TIPS and stuff for elxir

TESTING
 * mix test

ISSUES
 * project and file names with dashes (-) cause problems with unhelpful error messages


## Lists

l = [" abc"]
Enum.each(l, fn(x) -> IO.puts String.strip(x)  end)

## install

make PREFIX=/path/somewhere install

### mix

install other tasks for easy use

```mix do archive, local.install```
