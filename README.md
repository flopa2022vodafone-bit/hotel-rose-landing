import React from 'react';
<html>
export default function HotelRose() {
  return (
    <div className="min-h-screen bg-emerald-900 p-8 flex items-start justify-center">
      <div className="max-w-6xl w-full grid grid-cols-12 gap-6 items-start">
        {/* Left: Большое фото */}
        <div className="col-span-5 bg-white/0 rounded-md overflow-hidden shadow-lg">
          <img
            src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=600&h=420&q=80"
            alt="Modern villa with pool"
            className="w-full h-full object-cover block"
            style={{ height: 420 }}
          />
        </div>

        {/* Центр: Инфо-карта */}
        <div
          className="col-span-5 bg-gray-100 rounded-md p-6 shadow-md flex flex-col justify-between"
          style={{ height: 420 }}
        >
          <header className="mb-2">
            <div className="flex items-center gap-3">
              <div className="text-2xl font-semibold">
                hotel rose <span className="text-pink-500">♡</span>
              </div>
            </div>
            <div className="text-xs text-gray-500 mt-1">
              найкращий готель в україні
            </div>
          </header>

          <main className="flex-1 mt-4">
            <h2 className="text-2xl font-medium text-gray-800">вільні будинки</h2>
            <p className="text-gray-600 mt-2">вартість на добу</p>

            <div className="mt-4 grid grid-cols-2 gap-3 items-center">
              <div className="flex flex-col items-center">
                <img
                  src="https://images.pexels.com/photos/2102587/pexels-photo-2102587.jpeg?auto=compress&cs=tinysrgb&h=200&w=300"
                  alt="House option 1"
                  className="w-full rounded-md object-cover"
                  style={{ height: 100 }}
                />
                <div className="mt-2 text-sm font-bold">
                  $ <span className="text-2xl">100</span>
                </div>
              </div>

              <div className="flex flex-col items-center">
                <img
                  src="https://images.pexels.com/photos/259588/pexels-photo-259588.jpeg?auto=compress&cs=tinysrgb&h=200&w=300"
                  alt="House option 2"
                  className="w-full rounded-md object-cover"
                  style={{ height: 100 }}
                />
                <div className="mt-2 text-sm font-bold">
                  $ <span className="text-2xl">150</span>
                </div>
              </div>
            </div>
          </main>

          <footer className="mt-4 text-sm text-gray-500">&nbsp;</footer>
        </div>

        {/* Право: Команда */}
        <div className="col-span-2 flex items-start justify-center">
          <aside
            className="bg-gray-200 rounded-md p-6 shadow-sm w-full max-w-xs"
            style={{ height: 200 }}
          >
            <h3 className="text-lg font-semibold mb-2">команда</h3>
            <ul className="text-gray-800 leading-relaxed">
              <li>антон сонячний</li>
              <li>микита кавун</li>
              <li>тимофій грибний</li>
              <li>саша лісний</li>
            </ul>
          </aside>
        </div>
      </div>
    </div>
    </html>
    
