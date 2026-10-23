# Awesome-Log-Analytics-Dashboards

$variants = @(
    'https://github.com/sindresorhus/awesome',
    'https://github.com/sindresorhus/awesome/',
    'https://github.com/sindresorhus/awesome#readme'
)
foreach ($v in $variants) {
    if ($content.Contains($v)) { $content = $content.Replace($v, $new) }
}
