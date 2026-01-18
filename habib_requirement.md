> 1. ,,po,se,r,be,c (posarbik)

> 1.1. `,,po,d,su,m(podsam)`

> 1.2. `,,se, me, t(samet)`

---

#### ex:1.1. `,,po,d,su,m(podsam)`

> ,,Products, ,,Diagnostic Test Kit, ,,Supplements, ,,Medical patch

#### ex:1.2. `,,se, me, t`

> ,,Services, ,,Med Ai-Rapid Test, ,,Telehealth

> ,,Research & development

### confusion

> Diagnostic kits, Supplements are these products? if products then it's coming based category as web has supplement page and Diagnostic kits page separately=> if this okay then again why sorting category as it create issue that is kit page will show supplement data and vice versa

> warehouse & country field not taking from product creation

> Med Ai-Rapid Test page ( selections sort by is it from backend? )

> Research & Development page & it's details page( is this static page)

> Add to cart & Check out page (You May Also Like is this dynamic or static)

> is cart data store in backend

> checkout page delivery information. is it every time coming from user manual input

> Contact Us page flow clarification

> order tracking flow clarification> is it manual tracking by admin> estimated delivery time how coming

### code understanding from backend

## prisma model understanding

> Coupon> Country > CountrySectionInfo> CountryCardInfo what't the use of these models? is it related habib project or not?

> user > accessiblePages AccessiblePages[] what the use of this> is it related habib project or not?

```
enum AccessiblePages {
  Dashboard
  OrderManagement
  ProductManagement
  UsersManagement
  PaymentManagement
  StaffManagement
  LocationManagement
  Settings
}
```
