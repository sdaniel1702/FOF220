import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";

export default function FaithOverFailureHome() {
  return (
    <div className="min-h-screen bg-black text-white p-8 space-y-12">
      <header className="text-center space-y-4">
        <h1 className="text-5xl font-bold">Built Different. Driven by Faith. Fueled by Failure.</h1>
        <p className="text-xl">Legacy-first. Kingdom-minded. Second to None.</p>
      </header>

      <section className="grid grid-cols-1 md:grid-cols-2 gap-8">
        <Card>
          <CardContent className="space-y-2">
            <h2 className="text-2xl font-semibold">Our Mission</h2>
            <p>Faith Over Failure exists to empower men and women to walk in bold, unshakable purpose. We’re here to kill excuses, build generational wealth, and honor God while doing it.</p>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="space-y-2">
            <h2 className="text-2xl font-semibold">220 Gear</h2>
            <p>Streetwear with scripture. Designs that speak. Drops that remind you who you are.</p>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="space-y-2">
            <h2 className="text-2xl font-semibold">The Movement</h2>
            <p>Weekly 220 Chat. Events. Speaking. Coaching. We’re not just building brand—we’re building lives.</p>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="space-y-2">
            <h2 className="text-2xl font-semibold">Join the Tribe</h2>
            <p>Free devotional emails. Faith-based business tips. Merch alerts. Kingdom connections.</p>
          </CardContent>
        </Card>
      </section>

      <section className="text-center space-y-4">
        <h2 className="text-3xl font-bold">Contact / Booking</h2>
        <p>For speaking, collabs, or prayer—reach out. We move with purpose, and we move together.</p>
        <Button variant="secondary">Contact Us</Button>
      </section>

      <footer className="text-center pt-12 border-t border-white mt-12">
        <p className="text-sm">FAITH OVER FAILURE | 220 | SECOND TO NONE</p>
        <p className="text-sm">Copyright © 2025. All Rights Reserved.</p>
      </footer>
    </div>
  );
}
