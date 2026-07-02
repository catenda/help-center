# Approvals page troubleshooting

## 1. **Submitting a new approval request**

When a new approval request is submitted for review where more than 1000 documents are added with the add documents button the following error will appear:

![New approval request error Workflow default workflow Submitter Title](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/01-submitting-a-new-approval-request.png)

It is only possible to submit the new approval request dialogue with up to 1000 document at a time. To submit an approval request with more than 1000 documents, first add up to 1000 documents to the new approval request dialogue and save as draft. Go to the draft approval page of the document and add as many documents as desired before submitting the approval request.

## 2. **Overview tab - Closing an approval request**

When closing an approval the publishing can fail. In the [overview tab](https://support.catenda.com/en/articles/12495126-overview-tab-in-an-approval-request) of the approval the following can then be seen:

![Publishing failed Published 1 document. Failed to update 1 document view details](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/02-overview-tab-closing-an-approval-request.png)

### 2.1 **A published revision already exists**

It is only possible to publish shared revisions in documents where the latest revision is a shared revision. If the revision in the approval, or any other shared revision after the previous published revision was published and a new major revision number was created this revision cannot become that next major revision number because it already exists and will fail. A shared revision can have been published as a result of the closing of a different approval request or by using the publish action in the documents table or in the revision info in the right menu of a revision.

## 3. **Documents tab**

### 3.1 **Document not found**

If a document that is part of an approval is deleted it can no longer be found and the content of the docuemnt will no longer be displayed on the file review page. This is what the document tab can look like when an document that is part of an approval has been deleted:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/03-document-not-found.png)

Documents that were added to an approval request and that were later deleted can either be recovered by an administrator or discarded from the approval request.

### 3.2 **Withdrawn revision**​

If a document revision that is part of an approval is withdrawn the revision number is struck through and the content of the document will no longer be displayed on the file review page. This is what the document tab can look like when an document that is part of an approval has been deleted:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/atct6we8/04-withdrawn-revision.png)

Document revisions that were added to an approval request and later withdrawn can be discarded from the approval request.
