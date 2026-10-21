# parcel-events

Parcel lifecycle: acceptance, cancellation, dispatch, and audit; isolated UX validation.

`specification.yaml` is the authoritative, self-contained AsyncAPI document.
The System provisions validation, temporary schema extraction, Apicurio publication,
and Microcks import. Never commit generated schemas. Main commits publish by commit
SHA; normal release tags retain the existing contract release convention.

Registry group: `io.github.contractfirstkafka.kafkaux.parceldispatch`. Contract artifact: `parcel-events`.
Payload IDs and serializer configuration are described in the platform AsyncAPI guide.
