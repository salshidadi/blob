# blob

I implemented the following interfaces:

bool blb_blob_jump(blb_blob_t *blob, int32_t value); \
bool blb_blob_create_new_range(blb_blob_t *blob, uint32_t start, uint32_t size, uint8_t step, bool fixed, uint8_t index); \
bool blb_blob_range_slide(blb_blob_t *blob, int32_t steps, uint8_t index); \
bool blb_blob_range_resize(blb_blob_t *blob, int32_t size, uint8_t index);\
bool blb_blob_block_put(blb_blob_t *blob, int32_t offset, uint8_t value);\
bool blb_blob_block_get(blb_blob_t *blob, int32_t offset, uint8_t *value);\
