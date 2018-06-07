---
Description: The BreakConnect method releases a pin from a connection.
ms.assetid: cc384786-9cba-4f68-9c60-740205b35661
title: CTransformFilter.BreakConnect method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# CTransformFilter.BreakConnect method

The `BreakConnect` method releases a pin from a connection.

## Syntax


```C++
virtual HRESULT BreakConnect(
   PIN_DIRECTION dir
);
```



## Parameters

<dl> <dt>

*dir* 
</dt> <dd>

Member of the [**PIN\_DIRECTION**](/windows/desktop/api/strmif/ne-strmif-_pindirection) enumerated type, specifying which pin connection was broken (input or output).

</dd> </dl>

## Return value

Returns S\_OK.

## Remarks

The [**CTransformInputPin::BreakConnect**](ctransforminputpin-breakconnect.md) and [**CTransformOutputPin::BreakConnect**](ctransformoutputpin-breakconnect.md) methods call this method when a pin connection is broken. This method does nothing in the base class. If you override the [**CheckConnect**](ctransformfilter-checkconnect.md) method, override this method to release any resources obtained in the **CheckConnect** method, including interface pointers.

## Requirements



|                    |                                                                                                                                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Transfrm.h (include Streams.h)</dt> </dl>                                                                                  |
| Library<br/> | <dl> <dt>Strmbase.lib (retail builds); </dt> <dt>Strmbasd.lib (debug builds)</dt> </dl> |



## See also

<dl> <dt>

[**CTransformFilter Class**](ctransformfilter.md)
</dt> </dl>

 

 



