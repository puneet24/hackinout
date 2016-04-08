
input.match(/.+pvid\s*(\d+)[^\d]+\s*((\d+,)*)(\d+)/)
tagged = $1.to_i
untagged = ($2+$3).split(',').map(&:to_i)
