<!--NOTE: This file is generated by rvv_intrinsic_gen.py-->

## Vector Mask Functions:

### [Vector Mask Load/Store Functions](../rvv-intrinsic-api.md#74-vector-mask-load-operations):

**Prototypes:**
``` C
vbool1_t vlm_v_b1 (const uint8_t *base, size_t vl);
vbool2_t vlm_v_b2 (const uint8_t *base, size_t vl);
vbool4_t vlm_v_b4 (const uint8_t *base, size_t vl);
vbool8_t vlm_v_b8 (const uint8_t *base, size_t vl);
vbool16_t vlm_v_b16 (const uint8_t *base, size_t vl);
vbool32_t vlm_v_b32 (const uint8_t *base, size_t vl);
vbool64_t vlm_v_b64 (const uint8_t *base, size_t vl);
void vsm_v_b1 (uint8_t *base, vbool1_t value, size_t vl);
void vsm_v_b2 (uint8_t *base, vbool2_t value, size_t vl);
void vsm_v_b4 (uint8_t *base, vbool4_t value, size_t vl);
void vsm_v_b8 (uint8_t *base, vbool8_t value, size_t vl);
void vsm_v_b16 (uint8_t *base, vbool16_t value, size_t vl);
void vsm_v_b32 (uint8_t *base, vbool32_t value, size_t vl);
void vsm_v_b64 (uint8_t *base, vbool64_t value, size_t vl);
```
### [Vector Mask-Register Logical Functions](../rvv-intrinsic-api.md#161-vector-mask-register-logical-operations):

**Prototypes:**
``` C
vbool1_t vmand_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t vmand_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t vmand_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t vmand_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t vmand_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t vmand_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t vmand_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t vmnand_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t vmnand_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t vmnand_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t vmnand_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t vmnand_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t vmnand_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t vmnand_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t vmandnot_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t vmandnot_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t vmandnot_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t vmandnot_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t vmandnot_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t vmandnot_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t vmandnot_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t vmxor_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t vmxor_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t vmxor_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t vmxor_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t vmxor_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t vmxor_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t vmxor_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t vmor_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t vmor_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t vmor_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t vmor_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t vmor_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t vmor_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t vmor_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t vmnor_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t vmnor_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t vmnor_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t vmnor_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t vmnor_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t vmnor_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t vmnor_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t vmornot_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t vmornot_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t vmornot_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t vmornot_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t vmornot_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t vmornot_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t vmornot_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t vmxnor_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t vmxnor_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t vmxnor_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t vmxnor_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t vmxnor_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t vmxnor_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t vmxnor_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t vmmv_m_b1 (vbool1_t op1, size_t vl);
vbool2_t vmmv_m_b2 (vbool2_t op1, size_t vl);
vbool4_t vmmv_m_b4 (vbool4_t op1, size_t vl);
vbool8_t vmmv_m_b8 (vbool8_t op1, size_t vl);
vbool16_t vmmv_m_b16 (vbool16_t op1, size_t vl);
vbool32_t vmmv_m_b32 (vbool32_t op1, size_t vl);
vbool64_t vmmv_m_b64 (vbool64_t op1, size_t vl);
vbool1_t vmclr_m_b1 (size_t vl);
vbool2_t vmclr_m_b2 (size_t vl);
vbool4_t vmclr_m_b4 (size_t vl);
vbool8_t vmclr_m_b8 (size_t vl);
vbool16_t vmclr_m_b16 (size_t vl);
vbool32_t vmclr_m_b32 (size_t vl);
vbool64_t vmclr_m_b64 (size_t vl);
vbool1_t vmset_m_b1 (size_t vl);
vbool2_t vmset_m_b2 (size_t vl);
vbool4_t vmset_m_b4 (size_t vl);
vbool8_t vmset_m_b8 (size_t vl);
vbool16_t vmset_m_b16 (size_t vl);
vbool32_t vmset_m_b32 (size_t vl);
vbool64_t vmset_m_b64 (size_t vl);
vbool1_t vmnot_m_b1 (vbool1_t op1, size_t vl);
vbool2_t vmnot_m_b2 (vbool2_t op1, size_t vl);
vbool4_t vmnot_m_b4 (vbool4_t op1, size_t vl);
vbool8_t vmnot_m_b8 (vbool8_t op1, size_t vl);
vbool16_t vmnot_m_b16 (vbool16_t op1, size_t vl);
vbool32_t vmnot_m_b32 (vbool32_t op1, size_t vl);
vbool64_t vmnot_m_b64 (vbool64_t op1, size_t vl);
```
### [Vector mask population count Functions](../rvv-intrinsic-api.md#162-vector-mask-population-count-vpopc):

**Prototypes:**
``` C
unsigned long vpopc_m_b1 (vbool1_t op1, size_t vl);
unsigned long vpopc_m_b2 (vbool2_t op1, size_t vl);
unsigned long vpopc_m_b4 (vbool4_t op1, size_t vl);
unsigned long vpopc_m_b8 (vbool8_t op1, size_t vl);
unsigned long vpopc_m_b16 (vbool16_t op1, size_t vl);
unsigned long vpopc_m_b32 (vbool32_t op1, size_t vl);
unsigned long vpopc_m_b64 (vbool64_t op1, size_t vl);
// masked functions
unsigned long vpopc_m_b1_m (vbool1_t mask, vbool1_t op1, size_t vl);
unsigned long vpopc_m_b2_m (vbool2_t mask, vbool2_t op1, size_t vl);
unsigned long vpopc_m_b4_m (vbool4_t mask, vbool4_t op1, size_t vl);
unsigned long vpopc_m_b8_m (vbool8_t mask, vbool8_t op1, size_t vl);
unsigned long vpopc_m_b16_m (vbool16_t mask, vbool16_t op1, size_t vl);
unsigned long vpopc_m_b32_m (vbool32_t mask, vbool32_t op1, size_t vl);
unsigned long vpopc_m_b64_m (vbool64_t mask, vbool64_t op1, size_t vl);
```
### [Find-first-set mask bit Functions](../rvv-intrinsic-api.md#163-vfirst-find-first-set-mask-bit):

**Prototypes:**
``` C
long vfirst_m_b1 (vbool1_t op1, size_t vl);
long vfirst_m_b2 (vbool2_t op1, size_t vl);
long vfirst_m_b4 (vbool4_t op1, size_t vl);
long vfirst_m_b8 (vbool8_t op1, size_t vl);
long vfirst_m_b16 (vbool16_t op1, size_t vl);
long vfirst_m_b32 (vbool32_t op1, size_t vl);
long vfirst_m_b64 (vbool64_t op1, size_t vl);
// masked functions
long vfirst_m_b1_m (vbool1_t mask, vbool1_t op1, size_t vl);
long vfirst_m_b2_m (vbool2_t mask, vbool2_t op1, size_t vl);
long vfirst_m_b4_m (vbool4_t mask, vbool4_t op1, size_t vl);
long vfirst_m_b8_m (vbool8_t mask, vbool8_t op1, size_t vl);
long vfirst_m_b16_m (vbool16_t mask, vbool16_t op1, size_t vl);
long vfirst_m_b32_m (vbool32_t mask, vbool32_t op1, size_t vl);
long vfirst_m_b64_m (vbool64_t mask, vbool64_t op1, size_t vl);
```
### [Set-before-first mask bit Functions](../rvv-intrinsic-api.md#164-vmsbfm-set-before-first-mask-bit):

**Prototypes:**
``` C
vbool1_t vmsbf_m_b1 (vbool1_t op1, size_t vl);
vbool2_t vmsbf_m_b2 (vbool2_t op1, size_t vl);
vbool4_t vmsbf_m_b4 (vbool4_t op1, size_t vl);
vbool8_t vmsbf_m_b8 (vbool8_t op1, size_t vl);
vbool16_t vmsbf_m_b16 (vbool16_t op1, size_t vl);
vbool32_t vmsbf_m_b32 (vbool32_t op1, size_t vl);
vbool64_t vmsbf_m_b64 (vbool64_t op1, size_t vl);
// masked functions
vbool1_t vmsbf_m_b1_m (vbool1_t mask, vbool1_t maskedoff, vbool1_t op1, size_t vl);
vbool2_t vmsbf_m_b2_m (vbool2_t mask, vbool2_t maskedoff, vbool2_t op1, size_t vl);
vbool4_t vmsbf_m_b4_m (vbool4_t mask, vbool4_t maskedoff, vbool4_t op1, size_t vl);
vbool8_t vmsbf_m_b8_m (vbool8_t mask, vbool8_t maskedoff, vbool8_t op1, size_t vl);
vbool16_t vmsbf_m_b16_m (vbool16_t mask, vbool16_t maskedoff, vbool16_t op1, size_t vl);
vbool32_t vmsbf_m_b32_m (vbool32_t mask, vbool32_t maskedoff, vbool32_t op1, size_t vl);
vbool64_t vmsbf_m_b64_m (vbool64_t mask, vbool64_t maskedoff, vbool64_t op1, size_t vl);
```
### [Set-including-first mask bit Functions](../rvv-intrinsic-api.md#165-vmsifm-set-including-first-mask-bit):

**Prototypes:**
``` C
vbool1_t vmsif_m_b1 (vbool1_t op1, size_t vl);
vbool2_t vmsif_m_b2 (vbool2_t op1, size_t vl);
vbool4_t vmsif_m_b4 (vbool4_t op1, size_t vl);
vbool8_t vmsif_m_b8 (vbool8_t op1, size_t vl);
vbool16_t vmsif_m_b16 (vbool16_t op1, size_t vl);
vbool32_t vmsif_m_b32 (vbool32_t op1, size_t vl);
vbool64_t vmsif_m_b64 (vbool64_t op1, size_t vl);
// masked functions
vbool1_t vmsif_m_b1_m (vbool1_t mask, vbool1_t maskedoff, vbool1_t op1, size_t vl);
vbool2_t vmsif_m_b2_m (vbool2_t mask, vbool2_t maskedoff, vbool2_t op1, size_t vl);
vbool4_t vmsif_m_b4_m (vbool4_t mask, vbool4_t maskedoff, vbool4_t op1, size_t vl);
vbool8_t vmsif_m_b8_m (vbool8_t mask, vbool8_t maskedoff, vbool8_t op1, size_t vl);
vbool16_t vmsif_m_b16_m (vbool16_t mask, vbool16_t maskedoff, vbool16_t op1, size_t vl);
vbool32_t vmsif_m_b32_m (vbool32_t mask, vbool32_t maskedoff, vbool32_t op1, size_t vl);
vbool64_t vmsif_m_b64_m (vbool64_t mask, vbool64_t maskedoff, vbool64_t op1, size_t vl);
```
### [Set-only-first mask bit Functions](../rvv-intrinsic-api.md#166-vmsofm-set-only-first-mask-bit):

**Prototypes:**
``` C
vbool1_t vmsof_m_b1 (vbool1_t op1, size_t vl);
vbool2_t vmsof_m_b2 (vbool2_t op1, size_t vl);
vbool4_t vmsof_m_b4 (vbool4_t op1, size_t vl);
vbool8_t vmsof_m_b8 (vbool8_t op1, size_t vl);
vbool16_t vmsof_m_b16 (vbool16_t op1, size_t vl);
vbool32_t vmsof_m_b32 (vbool32_t op1, size_t vl);
vbool64_t vmsof_m_b64 (vbool64_t op1, size_t vl);
// masked functions
vbool1_t vmsof_m_b1_m (vbool1_t mask, vbool1_t maskedoff, vbool1_t op1, size_t vl);
vbool2_t vmsof_m_b2_m (vbool2_t mask, vbool2_t maskedoff, vbool2_t op1, size_t vl);
vbool4_t vmsof_m_b4_m (vbool4_t mask, vbool4_t maskedoff, vbool4_t op1, size_t vl);
vbool8_t vmsof_m_b8_m (vbool8_t mask, vbool8_t maskedoff, vbool8_t op1, size_t vl);
vbool16_t vmsof_m_b16_m (vbool16_t mask, vbool16_t maskedoff, vbool16_t op1, size_t vl);
vbool32_t vmsof_m_b32_m (vbool32_t mask, vbool32_t maskedoff, vbool32_t op1, size_t vl);
vbool64_t vmsof_m_b64_m (vbool64_t mask, vbool64_t maskedoff, vbool64_t op1, size_t vl);
```
### [Vector Iota Functions](../rvv-intrinsic-api.md#168-vector-iota-operations):

**Prototypes:**
``` C
vuint8mf8_t viota_m_u8mf8 (vbool64_t op1, size_t vl);
vuint8mf4_t viota_m_u8mf4 (vbool32_t op1, size_t vl);
vuint8mf2_t viota_m_u8mf2 (vbool16_t op1, size_t vl);
vuint8m1_t viota_m_u8m1 (vbool8_t op1, size_t vl);
vuint8m2_t viota_m_u8m2 (vbool4_t op1, size_t vl);
vuint8m4_t viota_m_u8m4 (vbool2_t op1, size_t vl);
vuint8m8_t viota_m_u8m8 (vbool1_t op1, size_t vl);
vuint16mf4_t viota_m_u16mf4 (vbool64_t op1, size_t vl);
vuint16mf2_t viota_m_u16mf2 (vbool32_t op1, size_t vl);
vuint16m1_t viota_m_u16m1 (vbool16_t op1, size_t vl);
vuint16m2_t viota_m_u16m2 (vbool8_t op1, size_t vl);
vuint16m4_t viota_m_u16m4 (vbool4_t op1, size_t vl);
vuint16m8_t viota_m_u16m8 (vbool2_t op1, size_t vl);
vuint32mf2_t viota_m_u32mf2 (vbool64_t op1, size_t vl);
vuint32m1_t viota_m_u32m1 (vbool32_t op1, size_t vl);
vuint32m2_t viota_m_u32m2 (vbool16_t op1, size_t vl);
vuint32m4_t viota_m_u32m4 (vbool8_t op1, size_t vl);
vuint32m8_t viota_m_u32m8 (vbool4_t op1, size_t vl);
vuint64m1_t viota_m_u64m1 (vbool64_t op1, size_t vl);
vuint64m2_t viota_m_u64m2 (vbool32_t op1, size_t vl);
vuint64m4_t viota_m_u64m4 (vbool16_t op1, size_t vl);
vuint64m8_t viota_m_u64m8 (vbool8_t op1, size_t vl);
vuint8mf8_t viota_m_u8mf8_tu (vuint8mf8_t dest, vbool64_t op1, size_t vl);
vuint8mf4_t viota_m_u8mf4_tu (vuint8mf4_t dest, vbool32_t op1, size_t vl);
vuint8mf2_t viota_m_u8mf2_tu (vuint8mf2_t dest, vbool16_t op1, size_t vl);
vuint8m1_t viota_m_u8m1_tu (vuint8m1_t dest, vbool8_t op1, size_t vl);
vuint8m2_t viota_m_u8m2_tu (vuint8m2_t dest, vbool4_t op1, size_t vl);
vuint8m4_t viota_m_u8m4_tu (vuint8m4_t dest, vbool2_t op1, size_t vl);
vuint8m8_t viota_m_u8m8_tu (vuint8m8_t dest, vbool1_t op1, size_t vl);
vuint16mf4_t viota_m_u16mf4_tu (vuint16mf4_t dest, vbool64_t op1, size_t vl);
vuint16mf2_t viota_m_u16mf2_tu (vuint16mf2_t dest, vbool32_t op1, size_t vl);
vuint16m1_t viota_m_u16m1_tu (vuint16m1_t dest, vbool16_t op1, size_t vl);
vuint16m2_t viota_m_u16m2_tu (vuint16m2_t dest, vbool8_t op1, size_t vl);
vuint16m4_t viota_m_u16m4_tu (vuint16m4_t dest, vbool4_t op1, size_t vl);
vuint16m8_t viota_m_u16m8_tu (vuint16m8_t dest, vbool2_t op1, size_t vl);
vuint32mf2_t viota_m_u32mf2_tu (vuint32mf2_t dest, vbool64_t op1, size_t vl);
vuint32m1_t viota_m_u32m1_tu (vuint32m1_t dest, vbool32_t op1, size_t vl);
vuint32m2_t viota_m_u32m2_tu (vuint32m2_t dest, vbool16_t op1, size_t vl);
vuint32m4_t viota_m_u32m4_tu (vuint32m4_t dest, vbool8_t op1, size_t vl);
vuint32m8_t viota_m_u32m8_tu (vuint32m8_t dest, vbool4_t op1, size_t vl);
vuint64m1_t viota_m_u64m1_tu (vuint64m1_t dest, vbool64_t op1, size_t vl);
vuint64m2_t viota_m_u64m2_tu (vuint64m2_t dest, vbool32_t op1, size_t vl);
vuint64m4_t viota_m_u64m4_tu (vuint64m4_t dest, vbool16_t op1, size_t vl);
vuint64m8_t viota_m_u64m8_tu (vuint64m8_t dest, vbool8_t op1, size_t vl);
// masked functions
vuint8mf8_t viota_m_u8mf8_m (vbool64_t mask, vuint8mf8_t maskedoff, vbool64_t op1, size_t vl);
vuint8mf4_t viota_m_u8mf4_m (vbool32_t mask, vuint8mf4_t maskedoff, vbool32_t op1, size_t vl);
vuint8mf2_t viota_m_u8mf2_m (vbool16_t mask, vuint8mf2_t maskedoff, vbool16_t op1, size_t vl);
vuint8m1_t viota_m_u8m1_m (vbool8_t mask, vuint8m1_t maskedoff, vbool8_t op1, size_t vl);
vuint8m2_t viota_m_u8m2_m (vbool4_t mask, vuint8m2_t maskedoff, vbool4_t op1, size_t vl);
vuint8m4_t viota_m_u8m4_m (vbool2_t mask, vuint8m4_t maskedoff, vbool2_t op1, size_t vl);
vuint8m8_t viota_m_u8m8_m (vbool1_t mask, vuint8m8_t maskedoff, vbool1_t op1, size_t vl);
vuint16mf4_t viota_m_u16mf4_m (vbool64_t mask, vuint16mf4_t maskedoff, vbool64_t op1, size_t vl);
vuint16mf2_t viota_m_u16mf2_m (vbool32_t mask, vuint16mf2_t maskedoff, vbool32_t op1, size_t vl);
vuint16m1_t viota_m_u16m1_m (vbool16_t mask, vuint16m1_t maskedoff, vbool16_t op1, size_t vl);
vuint16m2_t viota_m_u16m2_m (vbool8_t mask, vuint16m2_t maskedoff, vbool8_t op1, size_t vl);
vuint16m4_t viota_m_u16m4_m (vbool4_t mask, vuint16m4_t maskedoff, vbool4_t op1, size_t vl);
vuint16m8_t viota_m_u16m8_m (vbool2_t mask, vuint16m8_t maskedoff, vbool2_t op1, size_t vl);
vuint32mf2_t viota_m_u32mf2_m (vbool64_t mask, vuint32mf2_t maskedoff, vbool64_t op1, size_t vl);
vuint32m1_t viota_m_u32m1_m (vbool32_t mask, vuint32m1_t maskedoff, vbool32_t op1, size_t vl);
vuint32m2_t viota_m_u32m2_m (vbool16_t mask, vuint32m2_t maskedoff, vbool16_t op1, size_t vl);
vuint32m4_t viota_m_u32m4_m (vbool8_t mask, vuint32m4_t maskedoff, vbool8_t op1, size_t vl);
vuint32m8_t viota_m_u32m8_m (vbool4_t mask, vuint32m8_t maskedoff, vbool4_t op1, size_t vl);
vuint64m1_t viota_m_u64m1_m (vbool64_t mask, vuint64m1_t maskedoff, vbool64_t op1, size_t vl);
vuint64m2_t viota_m_u64m2_m (vbool32_t mask, vuint64m2_t maskedoff, vbool32_t op1, size_t vl);
vuint64m4_t viota_m_u64m4_m (vbool16_t mask, vuint64m4_t maskedoff, vbool16_t op1, size_t vl);
vuint64m8_t viota_m_u64m8_m (vbool8_t mask, vuint64m8_t maskedoff, vbool8_t op1, size_t vl);
// masked functions
vuint8mf8_t viota_m_u8mf8_mt (vbool64_t mask, vuint8mf8_t maskedoff, vbool64_t op1, size_t vl, size_t ta);
vuint8mf4_t viota_m_u8mf4_mt (vbool32_t mask, vuint8mf4_t maskedoff, vbool32_t op1, size_t vl, size_t ta);
vuint8mf2_t viota_m_u8mf2_mt (vbool16_t mask, vuint8mf2_t maskedoff, vbool16_t op1, size_t vl, size_t ta);
vuint8m1_t viota_m_u8m1_mt (vbool8_t mask, vuint8m1_t maskedoff, vbool8_t op1, size_t vl, size_t ta);
vuint8m2_t viota_m_u8m2_mt (vbool4_t mask, vuint8m2_t maskedoff, vbool4_t op1, size_t vl, size_t ta);
vuint8m4_t viota_m_u8m4_mt (vbool2_t mask, vuint8m4_t maskedoff, vbool2_t op1, size_t vl, size_t ta);
vuint8m8_t viota_m_u8m8_mt (vbool1_t mask, vuint8m8_t maskedoff, vbool1_t op1, size_t vl, size_t ta);
vuint16mf4_t viota_m_u16mf4_mt (vbool64_t mask, vuint16mf4_t maskedoff, vbool64_t op1, size_t vl, size_t ta);
vuint16mf2_t viota_m_u16mf2_mt (vbool32_t mask, vuint16mf2_t maskedoff, vbool32_t op1, size_t vl, size_t ta);
vuint16m1_t viota_m_u16m1_mt (vbool16_t mask, vuint16m1_t maskedoff, vbool16_t op1, size_t vl, size_t ta);
vuint16m2_t viota_m_u16m2_mt (vbool8_t mask, vuint16m2_t maskedoff, vbool8_t op1, size_t vl, size_t ta);
vuint16m4_t viota_m_u16m4_mt (vbool4_t mask, vuint16m4_t maskedoff, vbool4_t op1, size_t vl, size_t ta);
vuint16m8_t viota_m_u16m8_mt (vbool2_t mask, vuint16m8_t maskedoff, vbool2_t op1, size_t vl, size_t ta);
vuint32mf2_t viota_m_u32mf2_mt (vbool64_t mask, vuint32mf2_t maskedoff, vbool64_t op1, size_t vl, size_t ta);
vuint32m1_t viota_m_u32m1_mt (vbool32_t mask, vuint32m1_t maskedoff, vbool32_t op1, size_t vl, size_t ta);
vuint32m2_t viota_m_u32m2_mt (vbool16_t mask, vuint32m2_t maskedoff, vbool16_t op1, size_t vl, size_t ta);
vuint32m4_t viota_m_u32m4_mt (vbool8_t mask, vuint32m4_t maskedoff, vbool8_t op1, size_t vl, size_t ta);
vuint32m8_t viota_m_u32m8_mt (vbool4_t mask, vuint32m8_t maskedoff, vbool4_t op1, size_t vl, size_t ta);
vuint64m1_t viota_m_u64m1_mt (vbool64_t mask, vuint64m1_t maskedoff, vbool64_t op1, size_t vl, size_t ta);
vuint64m2_t viota_m_u64m2_mt (vbool32_t mask, vuint64m2_t maskedoff, vbool32_t op1, size_t vl, size_t ta);
vuint64m4_t viota_m_u64m4_mt (vbool16_t mask, vuint64m4_t maskedoff, vbool16_t op1, size_t vl, size_t ta);
vuint64m8_t viota_m_u64m8_mt (vbool8_t mask, vuint64m8_t maskedoff, vbool8_t op1, size_t vl, size_t ta);
```
### [Vector Element Index Functions](../rvv-intrinsic-api.md#169-vector-element-index-operations):

**Prototypes:**
``` C
vuint8mf8_t vid_v_u8mf8 (size_t vl);
vuint8mf4_t vid_v_u8mf4 (size_t vl);
vuint8mf2_t vid_v_u8mf2 (size_t vl);
vuint8m1_t vid_v_u8m1 (size_t vl);
vuint8m2_t vid_v_u8m2 (size_t vl);
vuint8m4_t vid_v_u8m4 (size_t vl);
vuint8m8_t vid_v_u8m8 (size_t vl);
vuint16mf4_t vid_v_u16mf4 (size_t vl);
vuint16mf2_t vid_v_u16mf2 (size_t vl);
vuint16m1_t vid_v_u16m1 (size_t vl);
vuint16m2_t vid_v_u16m2 (size_t vl);
vuint16m4_t vid_v_u16m4 (size_t vl);
vuint16m8_t vid_v_u16m8 (size_t vl);
vuint32mf2_t vid_v_u32mf2 (size_t vl);
vuint32m1_t vid_v_u32m1 (size_t vl);
vuint32m2_t vid_v_u32m2 (size_t vl);
vuint32m4_t vid_v_u32m4 (size_t vl);
vuint32m8_t vid_v_u32m8 (size_t vl);
vuint64m1_t vid_v_u64m1 (size_t vl);
vuint64m2_t vid_v_u64m2 (size_t vl);
vuint64m4_t vid_v_u64m4 (size_t vl);
vuint64m8_t vid_v_u64m8 (size_t vl);
vuint8mf8_t vid_v_u8mf8_tu (vuint8mf8_t dest, size_t vl);
vuint8mf4_t vid_v_u8mf4_tu (vuint8mf4_t dest, size_t vl);
vuint8mf2_t vid_v_u8mf2_tu (vuint8mf2_t dest, size_t vl);
vuint8m1_t vid_v_u8m1_tu (vuint8m1_t dest, size_t vl);
vuint8m2_t vid_v_u8m2_tu (vuint8m2_t dest, size_t vl);
vuint8m4_t vid_v_u8m4_tu (vuint8m4_t dest, size_t vl);
vuint8m8_t vid_v_u8m8_tu (vuint8m8_t dest, size_t vl);
vuint16mf4_t vid_v_u16mf4_tu (vuint16mf4_t dest, size_t vl);
vuint16mf2_t vid_v_u16mf2_tu (vuint16mf2_t dest, size_t vl);
vuint16m1_t vid_v_u16m1_tu (vuint16m1_t dest, size_t vl);
vuint16m2_t vid_v_u16m2_tu (vuint16m2_t dest, size_t vl);
vuint16m4_t vid_v_u16m4_tu (vuint16m4_t dest, size_t vl);
vuint16m8_t vid_v_u16m8_tu (vuint16m8_t dest, size_t vl);
vuint32mf2_t vid_v_u32mf2_tu (vuint32mf2_t dest, size_t vl);
vuint32m1_t vid_v_u32m1_tu (vuint32m1_t dest, size_t vl);
vuint32m2_t vid_v_u32m2_tu (vuint32m2_t dest, size_t vl);
vuint32m4_t vid_v_u32m4_tu (vuint32m4_t dest, size_t vl);
vuint32m8_t vid_v_u32m8_tu (vuint32m8_t dest, size_t vl);
vuint64m1_t vid_v_u64m1_tu (vuint64m1_t dest, size_t vl);
vuint64m2_t vid_v_u64m2_tu (vuint64m2_t dest, size_t vl);
vuint64m4_t vid_v_u64m4_tu (vuint64m4_t dest, size_t vl);
vuint64m8_t vid_v_u64m8_tu (vuint64m8_t dest, size_t vl);
// masked functions
vuint8mf8_t vid_v_u8mf8_m (vbool64_t mask, vuint8mf8_t maskedoff, size_t vl);
vuint8mf4_t vid_v_u8mf4_m (vbool32_t mask, vuint8mf4_t maskedoff, size_t vl);
vuint8mf2_t vid_v_u8mf2_m (vbool16_t mask, vuint8mf2_t maskedoff, size_t vl);
vuint8m1_t vid_v_u8m1_m (vbool8_t mask, vuint8m1_t maskedoff, size_t vl);
vuint8m2_t vid_v_u8m2_m (vbool4_t mask, vuint8m2_t maskedoff, size_t vl);
vuint8m4_t vid_v_u8m4_m (vbool2_t mask, vuint8m4_t maskedoff, size_t vl);
vuint8m8_t vid_v_u8m8_m (vbool1_t mask, vuint8m8_t maskedoff, size_t vl);
vuint16mf4_t vid_v_u16mf4_m (vbool64_t mask, vuint16mf4_t maskedoff, size_t vl);
vuint16mf2_t vid_v_u16mf2_m (vbool32_t mask, vuint16mf2_t maskedoff, size_t vl);
vuint16m1_t vid_v_u16m1_m (vbool16_t mask, vuint16m1_t maskedoff, size_t vl);
vuint16m2_t vid_v_u16m2_m (vbool8_t mask, vuint16m2_t maskedoff, size_t vl);
vuint16m4_t vid_v_u16m4_m (vbool4_t mask, vuint16m4_t maskedoff, size_t vl);
vuint16m8_t vid_v_u16m8_m (vbool2_t mask, vuint16m8_t maskedoff, size_t vl);
vuint32mf2_t vid_v_u32mf2_m (vbool64_t mask, vuint32mf2_t maskedoff, size_t vl);
vuint32m1_t vid_v_u32m1_m (vbool32_t mask, vuint32m1_t maskedoff, size_t vl);
vuint32m2_t vid_v_u32m2_m (vbool16_t mask, vuint32m2_t maskedoff, size_t vl);
vuint32m4_t vid_v_u32m4_m (vbool8_t mask, vuint32m4_t maskedoff, size_t vl);
vuint32m8_t vid_v_u32m8_m (vbool4_t mask, vuint32m8_t maskedoff, size_t vl);
vuint64m1_t vid_v_u64m1_m (vbool64_t mask, vuint64m1_t maskedoff, size_t vl);
vuint64m2_t vid_v_u64m2_m (vbool32_t mask, vuint64m2_t maskedoff, size_t vl);
vuint64m4_t vid_v_u64m4_m (vbool16_t mask, vuint64m4_t maskedoff, size_t vl);
vuint64m8_t vid_v_u64m8_m (vbool8_t mask, vuint64m8_t maskedoff, size_t vl);
// masked functions
vuint8mf8_t vid_v_u8mf8_mt (vbool64_t mask, vuint8mf8_t maskedoff, size_t vl, size_t ta);
vuint8mf4_t vid_v_u8mf4_mt (vbool32_t mask, vuint8mf4_t maskedoff, size_t vl, size_t ta);
vuint8mf2_t vid_v_u8mf2_mt (vbool16_t mask, vuint8mf2_t maskedoff, size_t vl, size_t ta);
vuint8m1_t vid_v_u8m1_mt (vbool8_t mask, vuint8m1_t maskedoff, size_t vl, size_t ta);
vuint8m2_t vid_v_u8m2_mt (vbool4_t mask, vuint8m2_t maskedoff, size_t vl, size_t ta);
vuint8m4_t vid_v_u8m4_mt (vbool2_t mask, vuint8m4_t maskedoff, size_t vl, size_t ta);
vuint8m8_t vid_v_u8m8_mt (vbool1_t mask, vuint8m8_t maskedoff, size_t vl, size_t ta);
vuint16mf4_t vid_v_u16mf4_mt (vbool64_t mask, vuint16mf4_t maskedoff, size_t vl, size_t ta);
vuint16mf2_t vid_v_u16mf2_mt (vbool32_t mask, vuint16mf2_t maskedoff, size_t vl, size_t ta);
vuint16m1_t vid_v_u16m1_mt (vbool16_t mask, vuint16m1_t maskedoff, size_t vl, size_t ta);
vuint16m2_t vid_v_u16m2_mt (vbool8_t mask, vuint16m2_t maskedoff, size_t vl, size_t ta);
vuint16m4_t vid_v_u16m4_mt (vbool4_t mask, vuint16m4_t maskedoff, size_t vl, size_t ta);
vuint16m8_t vid_v_u16m8_mt (vbool2_t mask, vuint16m8_t maskedoff, size_t vl, size_t ta);
vuint32mf2_t vid_v_u32mf2_mt (vbool64_t mask, vuint32mf2_t maskedoff, size_t vl, size_t ta);
vuint32m1_t vid_v_u32m1_mt (vbool32_t mask, vuint32m1_t maskedoff, size_t vl, size_t ta);
vuint32m2_t vid_v_u32m2_mt (vbool16_t mask, vuint32m2_t maskedoff, size_t vl, size_t ta);
vuint32m4_t vid_v_u32m4_mt (vbool8_t mask, vuint32m4_t maskedoff, size_t vl, size_t ta);
vuint32m8_t vid_v_u32m8_mt (vbool4_t mask, vuint32m8_t maskedoff, size_t vl, size_t ta);
vuint64m1_t vid_v_u64m1_mt (vbool64_t mask, vuint64m1_t maskedoff, size_t vl, size_t ta);
vuint64m2_t vid_v_u64m2_mt (vbool32_t mask, vuint64m2_t maskedoff, size_t vl, size_t ta);
vuint64m4_t vid_v_u64m4_mt (vbool16_t mask, vuint64m4_t maskedoff, size_t vl, size_t ta);
vuint64m8_t vid_v_u64m8_mt (vbool8_t mask, vuint64m8_t maskedoff, size_t vl, size_t ta);
```