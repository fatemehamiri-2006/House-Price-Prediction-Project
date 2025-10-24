House Price Prediction Project

توضیح پروژه:
این پروژه با هدف پیش‌بینی قیمت خانه‌ها بر اساس ویژگی‌های مختلف خانه‌ها ساخته شده است.
با استفاده از داده‌های واقعی و تکنیک‌های Machine Learning، مدل توانایی پیش‌بینی قیمت خانه‌ها را دارد.

ویژگی‌ها (Features)

LotFrontage: طول جلوی زمین

Alley: نوع کوچه

MasVnrType: نوع سنگ نما

MasVnrArea: مساحت سنگ نما

BsmtQual, BsmtCond, BsmtExposure, BsmtFinType1, BsmtFinType2: مشخصات زیرزمین

Electrical: نوع سیستم برق

FireplaceQu: کیفیت شومینه

GarageYrBlt, GarageType, GarageFinish, GarageQual, GarageCond: مشخصات گاراژ

PoolQC: کیفیت استخر

Fence: نوع فنس

MiscFeature: ویژگی‌های اضافی

توجه: برخی از ویژگی‌ها عددی و برخی دسته‌ای هستند، برای مدل آماده‌سازی شدند.

هدف (Target)

SalePrice: قیمت فروش خانه

کتابخانه‌ها و ابزارها

Python (pandas, numpy, matplotlib, seaborn)

Scikit-Learn (LinearRegression, train_test_split, StandardScaler)

openpyxl برای ذخیره خروجی Excel

مراحل اجرای پروژه

پاکسازی داده‌ها و پر کردن Null‌ها

تبدیل ویژگی‌های دسته‌ای به عددی (با fillna و encoding ساده)

تقسیم داده به train و test

آموزش مدل Linear Regression

پیش‌بینی قیمت خانه‌ها

تحلیل مدل با نمودارها

Actual vs Predicted

Residual Plot

Histogram خطاها

ذخیره پیش‌بینی‌ها در فایل Excel (HousePrice_Predictions.xlsx)
