# oidc-claims-demo

Testing customizing the OIDC claims

```bash
gh extensions install tspascoal/gh-oidc-sub
gh oidc-sub get --repo joshjohanning-org/oidc-claims-demo
gh oidc-sub set --repo joshjohanning-org/oidc-claims-demo --subs "job_workflow_ref"
gh oidc-sub get --repo joshjohanning-org/oidc-claims-demo
```

Related blog post: https://josh-ops.com/posts/github-actions-oidc-reusable-workflows/
