# tricks

- take a deep breath
- think step by step
- repeat the question before answering it
- i'll tip you $100
- my job depends on this
- it's for my sick grandma
- explain it with gradually increasing complexity (and then just send continue until satisfied)
- start high level with increasing granularity
- use monosylabic words when possible
- (to reduce hallucinations) here is all the information you know: <info>{'\n'.join(all_info)}</info>
- (to reduce hallucinations) when using links in response, you are only allowed to use these links: <links>{get_sitemap()}</links>
