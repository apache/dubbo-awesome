# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.174 ops/ms
# Warmup Iteration   2: 3.062 ops/ms
# Warmup Iteration   3: 5.679 ops/ms
Iteration   1: 5.608 ops/ms
Iteration   2: 5.672 ops/ms
Iteration   3: 5.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.752 ±(99.9%) 3.580 ops/ms [Average]
  (min, avg, max) = (5.608, 5.752, 5.975), stdev = 0.196
  CI (99.9%): [2.172, 9.332] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.650 ops/ms
# Warmup Iteration   2: 4.962 ops/ms
# Warmup Iteration   3: 5.959 ops/ms
Iteration   1: 6.204 ops/ms
Iteration   2: 6.323 ops/ms
Iteration   3: 6.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.239 ±(99.9%) 1.323 ops/ms [Average]
  (min, avg, max) = (6.191, 6.239, 6.323), stdev = 0.073
  CI (99.9%): [4.916, 7.562] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.676 ops/ms
# Warmup Iteration   2: 4.597 ops/ms
# Warmup Iteration   3: 5.556 ops/ms
Iteration   1: 5.882 ops/ms
Iteration   2: 5.836 ops/ms
Iteration   3: 5.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.837 ±(99.9%) 0.823 ops/ms [Average]
  (min, avg, max) = (5.792, 5.837, 5.882), stdev = 0.045
  CI (99.9%): [5.013, 6.660] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.619 ops/ms
# Warmup Iteration   2: 4.337 ops/ms
# Warmup Iteration   3: 5.082 ops/ms
Iteration   1: 5.016 ops/ms
Iteration   2: 5.169 ops/ms
Iteration   3: 5.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.075 ±(99.9%) 1.492 ops/ms [Average]
  (min, avg, max) = (5.016, 5.075, 5.169), stdev = 0.082
  CI (99.9%): [3.583, 6.567] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 19.504 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.795 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.613 ±(99.9%) 0.014 ms/op
Iteration   1: 5.420 ±(99.9%) 0.013 ms/op
Iteration   2: 5.411 ±(99.9%) 0.010 ms/op
Iteration   3: 5.399 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.410 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (5.399, 5.410, 5.420), stdev = 0.011
  CI (99.9%): [5.216, 5.604] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 17.204 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 6.410 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.276 ±(99.9%) 0.009 ms/op
Iteration   1: 5.210 ±(99.9%) 0.011 ms/op
Iteration   2: 5.179 ±(99.9%) 0.013 ms/op
Iteration   3: 5.028 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.139 ±(99.9%) 1.776 ms/op [Average]
  (min, avg, max) = (5.028, 5.139, 5.210), stdev = 0.097
  CI (99.9%): [3.363, 6.915] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.541 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 7.087 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.648 ±(99.9%) 0.012 ms/op
Iteration   1: 5.399 ±(99.9%) 0.014 ms/op
Iteration   2: 5.248 ±(99.9%) 0.012 ms/op
Iteration   3: 5.513 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.387 ±(99.9%) 2.429 ms/op [Average]
  (min, avg, max) = (5.248, 5.387, 5.513), stdev = 0.133
  CI (99.9%): [2.958, 7.816] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.733 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 7.409 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.530 ±(99.9%) 0.013 ms/op
Iteration   1: 6.540 ±(99.9%) 0.010 ms/op
Iteration   2: 6.306 ±(99.9%) 0.019 ms/op
Iteration   3: 6.144 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.330 ±(99.9%) 3.636 ms/op [Average]
  (min, avg, max) = (6.144, 6.330, 6.540), stdev = 0.199
  CI (99.9%): [2.694, 9.965] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.548 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 6.802 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.970 ±(99.9%) 0.028 ms/op
Iteration   1: 5.509 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.327 ms/op
                 createUser·p0.50:   5.169 ms/op
                 createUser·p0.90:   6.791 ms/op
                 createUser·p0.95:   8.061 ms/op
                 createUser·p0.99:   11.000 ms/op
                 createUser·p0.999:  23.788 ms/op
                 createUser·p0.9999: 26.744 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   2: 5.414 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   5.095 ms/op
                 createUser·p0.90:   6.627 ms/op
                 createUser·p0.95:   7.438 ms/op
                 createUser·p0.99:   9.896 ms/op
                 createUser·p0.999:  24.991 ms/op
                 createUser·p0.9999: 30.748 ms/op
                 createUser·p1.00:   31.130 ms/op

Iteration   3: 5.450 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.306 ms/op
                 createUser·p0.50:   5.112 ms/op
                 createUser·p0.90:   6.685 ms/op
                 createUser·p0.95:   7.635 ms/op
                 createUser·p0.99:   11.076 ms/op
                 createUser·p0.999:  26.464 ms/op
                 createUser·p0.9999: 32.486 ms/op
                 createUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175867
  mean =      5.457 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 74516 
    [ 5.000,  7.500) = 91284 
    [ 7.500, 10.000) = 7662 
    [10.000, 12.500) = 1583 
    [12.500, 15.000) = 389 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =     10.813 ms/op
     p(99.9000) =     24.515 ms/op
     p(99.9900) =     31.897 ms/op
     p(99.9990) =     32.743 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.264 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 6.036 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.434 ±(99.9%) 0.021 ms/op
Iteration   1: 5.176 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.974 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   6.365 ms/op
                 existUser·p0.95:   7.201 ms/op
                 existUser·p0.99:   9.699 ms/op
                 existUser·p0.999:  19.930 ms/op
                 existUser·p0.9999: 26.733 ms/op
                 existUser·p1.00:   28.541 ms/op

Iteration   2: 5.213 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.531 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.423 ms/op
                 existUser·p0.95:   7.324 ms/op
                 existUser·p0.99:   9.650 ms/op
                 existUser·p0.999:  25.492 ms/op
                 existUser·p0.9999: 28.126 ms/op
                 existUser·p1.00:   29.098 ms/op

Iteration   3: 5.245 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.690 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.436 ms/op
                 existUser·p0.95:   7.537 ms/op
                 existUser·p0.99:   10.011 ms/op
                 existUser·p0.999:  24.670 ms/op
                 existUser·p0.9999: 35.455 ms/op
                 existUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184191
  mean =      5.211 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 106414 
    [ 5.000,  7.500) = 69353 
    [ 7.500, 10.000) = 6768 
    [10.000, 12.500) = 924 
    [12.500, 15.000) = 347 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     33.592 ms/op
     p(99.9990) =     35.727 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.863 ±(99.9%) 0.308 ms/op
# Warmup Iteration   2: 6.980 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.617 ±(99.9%) 0.020 ms/op
Iteration   1: 5.607 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.613 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   6.668 ms/op
                 getUser·p0.95:   7.569 ms/op
                 getUser·p0.99:   10.699 ms/op
                 getUser·p0.999:  23.724 ms/op
                 getUser·p0.9999: 27.007 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   2: 5.451 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.911 ms/op
                 getUser·p0.50:   5.087 ms/op
                 getUser·p0.90:   6.889 ms/op
                 getUser·p0.95:   7.922 ms/op
                 getUser·p0.99:   10.813 ms/op
                 getUser·p0.999:  25.924 ms/op
                 getUser·p0.9999: 30.278 ms/op
                 getUser·p1.00:   30.802 ms/op

Iteration   3: 5.530 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.310 ms/op
                 getUser·p0.50:   5.169 ms/op
                 getUser·p0.90:   6.971 ms/op
                 getUser·p0.95:   7.905 ms/op
                 getUser·p0.99:   10.551 ms/op
                 getUser·p0.999:  28.443 ms/op
                 getUser·p0.9999: 32.156 ms/op
                 getUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173635
  mean =      5.529 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 69268 
    [ 5.000,  7.500) = 93282 
    [ 7.500, 10.000) = 8788 
    [10.000, 12.500) = 1413 
    [12.500, 15.000) = 542 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.832 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     25.657 ms/op
     p(99.9900) =     30.790 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.210 ±(99.9%) 0.335 ms/op
# Warmup Iteration   2: 7.656 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 7.077 ±(99.9%) 0.037 ms/op
Iteration   1: 6.472 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.105 ms/op
                 listUser·p0.50:   6.029 ms/op
                 listUser·p0.90:   8.307 ms/op
                 listUser·p0.95:   9.421 ms/op
                 listUser·p0.99:   12.632 ms/op
                 listUser·p0.999:  27.034 ms/op
                 listUser·p0.9999: 35.729 ms/op
                 listUser·p1.00:   38.339 ms/op

Iteration   2: 6.219 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   5.865 ms/op
                 listUser·p0.90:   7.471 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   11.698 ms/op
                 listUser·p0.999:  29.041 ms/op
                 listUser·p0.9999: 33.938 ms/op
                 listUser·p1.00:   35.062 ms/op

Iteration   3: 6.228 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.236 ms/op
                 listUser·p0.50:   5.947 ms/op
                 listUser·p0.90:   7.193 ms/op
                 listUser·p0.95:   8.208 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  26.143 ms/op
                 listUser·p0.9999: 36.682 ms/op
                 listUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152231
  mean =      6.304 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 6876 
    [ 5.000,  7.500) = 128841 
    [ 7.500, 10.000) = 12444 
    [10.000, 12.500) = 2792 
    [12.500, 15.000) = 721 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.931 ms/op
     p(50.0000) =      5.947 ms/op
     p(90.0000) =      7.619 ms/op
     p(95.0000) =      8.978 ms/op
     p(99.0000) =     11.960 ms/op
     p(99.9000) =     27.394 ms/op
     p(99.9900) =     35.702 ms/op
     p(99.9990) =     38.133 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.752 ± 3.580  ops/ms
ClientPb.existUser                       thrpt       3   6.239 ± 1.323  ops/ms
ClientPb.getUser                         thrpt       3   5.837 ± 0.823  ops/ms
ClientPb.listUser                        thrpt       3   5.075 ± 1.492  ops/ms
ClientPb.createUser                       avgt       3   5.410 ± 0.194   ms/op
ClientPb.existUser                        avgt       3   5.139 ± 1.776   ms/op
ClientPb.getUser                          avgt       3   5.387 ± 2.429   ms/op
ClientPb.listUser                         avgt       3   6.330 ± 3.636   ms/op
ClientPb.createUser                     sample  175867   5.457 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.335           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.120           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.685           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.733           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.813           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.515           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.897           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.768           ms/op
ClientPb.existUser                      sample  184191   5.211 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.690           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.874           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.406           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.365           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.781           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.021           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.592           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.783           ms/op
ClientPb.getUser                        sample  173635   5.529 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.911           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.218           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.816           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.832           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.699           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.657           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.790           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.554           ms/op
ClientPb.listUser                       sample  152231   6.304 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.931           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.947           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.619           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.978           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.960           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.394           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.702           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.339           ms/op
