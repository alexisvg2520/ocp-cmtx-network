# cmtx-network
Chart Helm con **NetworkPolicies** para CMTX en `ecuaalejo2013-dev`.

## Qué incluye
- Default deny (ingress/egress)
- DNS egress
- Router → Frontend (ingress)
- Frontend → API (egress/ingress)
- API → DATA (egress/ingress)
- DATA → Mongo (egress/ingress)

