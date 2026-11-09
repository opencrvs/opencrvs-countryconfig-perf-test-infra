ARG CORE_IMAGE_TAG
FROM ghcr.io/opencrvs/ocrvs-testland:${CORE_IMAGE_TAG}

COPY --chown=node:node employees/ /app/packages/testland/src/data-seeding/employees/source/
COPY --chown=node:node locations/ /app/packages/testland/src/data-seeding/locations/source/