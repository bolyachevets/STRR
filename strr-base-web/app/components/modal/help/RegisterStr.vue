<template>
  <ModalBase :title="$t('modal.help.registerStr.title')">
    <div class="space-y-8">
      <i18n-t keypath="modal.help.registerStr.content" tag="p" scope="global">
        <template #link>
          <a
            href="https://www.STRregistry.gov.bc.ca"
            target="_blank"
            class="text-bcGovColor-activeBlue underline"
          >
            STRregistry.gov.bc.ca
          </a>
        </template>
      </i18n-t>
      <div class="h-20 w-full">
        <ContactSTRR />
      </div>
    </div>
  </ModalBase>
</template>
