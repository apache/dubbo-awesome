# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.078 ops/ms
# Warmup Iteration   2: 2.448 ops/ms
# Warmup Iteration   3: 5.033 ops/ms
Iteration   1: 5.364 ops/ms
Iteration   2: 5.420 ops/ms
Iteration   3: 5.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.449 ±(99.9%) 1.876 ops/ms [Average]
  (min, avg, max) = (5.364, 5.449, 5.563), stdev = 0.103
  CI (99.9%): [3.574, 7.325] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.786 ops/ms
# Warmup Iteration   2: 4.864 ops/ms
# Warmup Iteration   3: 5.640 ops/ms
Iteration   1: 6.195 ops/ms
Iteration   2: 5.948 ops/ms
Iteration   3: 5.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.979 ±(99.9%) 3.705 ops/ms [Average]
  (min, avg, max) = (5.792, 5.979, 6.195), stdev = 0.203
  CI (99.9%): [2.274, 9.684] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.592 ops/ms
# Warmup Iteration   2: 4.603 ops/ms
# Warmup Iteration   3: 5.474 ops/ms
Iteration   1: 5.539 ops/ms
Iteration   2: 5.368 ops/ms
Iteration   3: 5.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.487 ±(99.9%) 1.886 ops/ms [Average]
  (min, avg, max) = (5.368, 5.487, 5.554), stdev = 0.103
  CI (99.9%): [3.601, 7.373] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.490 ops/ms
# Warmup Iteration   2: 3.851 ops/ms
# Warmup Iteration   3: 4.762 ops/ms
Iteration   1: 4.750 ops/ms
Iteration   2: 4.805 ops/ms
Iteration   3: 4.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.815 ±(99.9%) 1.281 ops/ms [Average]
  (min, avg, max) = (4.750, 4.815, 4.890), stdev = 0.070
  CI (99.9%): [3.534, 6.096] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 19.319 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 7.125 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.818 ±(99.9%) 0.016 ms/op
Iteration   1: 5.735 ±(99.9%) 0.013 ms/op
Iteration   2: 5.781 ±(99.9%) 0.018 ms/op
Iteration   3: 5.562 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.693 ±(99.9%) 2.106 ms/op [Average]
  (min, avg, max) = (5.562, 5.693, 5.781), stdev = 0.115
  CI (99.9%): [3.587, 7.799] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 14.832 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.242 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.574 ±(99.9%) 0.012 ms/op
Iteration   1: 5.724 ±(99.9%) 0.009 ms/op
Iteration   2: 5.551 ±(99.9%) 0.011 ms/op
Iteration   3: 5.606 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.627 ±(99.9%) 1.612 ms/op [Average]
  (min, avg, max) = (5.551, 5.627, 5.724), stdev = 0.088
  CI (99.9%): [4.015, 7.239] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.372 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 6.731 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.609 ±(99.9%) 0.010 ms/op
Iteration   1: 5.833 ±(99.9%) 0.013 ms/op
Iteration   2: 5.605 ±(99.9%) 0.010 ms/op
Iteration   3: 5.492 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.643 ±(99.9%) 3.171 ms/op [Average]
  (min, avg, max) = (5.492, 5.643, 5.833), stdev = 0.174
  CI (99.9%): [2.472, 8.815] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.401 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 7.812 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 6.836 ±(99.9%) 0.013 ms/op
Iteration   1: 6.500 ±(99.9%) 0.022 ms/op
Iteration   2: 6.463 ±(99.9%) 0.014 ms/op
Iteration   3: 6.472 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.478 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (6.463, 6.478, 6.500), stdev = 0.019
  CI (99.9%): [6.133, 6.824] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.132 ±(99.9%) 0.334 ms/op
# Warmup Iteration   2: 6.952 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.197 ±(99.9%) 0.029 ms/op
Iteration   1: 5.670 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.384 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   7.299 ms/op
                 createUser·p0.95:   8.520 ms/op
                 createUser·p0.99:   11.452 ms/op
                 createUser·p0.999:  23.381 ms/op
                 createUser·p0.9999: 28.421 ms/op
                 createUser·p1.00:   31.130 ms/op

Iteration   2: 5.825 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.449 ms/op
                 createUser·p0.50:   5.546 ms/op
                 createUser·p0.90:   7.340 ms/op
                 createUser·p0.95:   8.282 ms/op
                 createUser·p0.99:   11.108 ms/op
                 createUser·p0.999:  16.810 ms/op
                 createUser·p0.9999: 30.589 ms/op
                 createUser·p1.00:   31.850 ms/op

Iteration   3: 5.775 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.236 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   7.430 ms/op
                 createUser·p0.95:   8.634 ms/op
                 createUser·p0.99:   12.288 ms/op
                 createUser·p0.999:  32.604 ms/op
                 createUser·p0.9999: 36.761 ms/op
                 createUser·p1.00:   52.494 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 166722
  mean =      5.756 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 60369 
    [ 5.000, 10.000) = 102682 
    [10.000, 15.000) = 3162 
    [15.000, 20.000) = 257 
    [20.000, 25.000) = 88 
    [25.000, 30.000) = 88 
    [30.000, 35.000) = 57 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.236 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      7.356 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.534 ms/op
     p(99.9000) =     24.805 ms/op
     p(99.9900) =     35.345 ms/op
     p(99.9990) =     42.131 ms/op
     p(99.9999) =     52.494 ms/op
    p(100.0000) =     52.494 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 19.747 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 6.940 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.843 ±(99.9%) 0.022 ms/op
Iteration   1: 5.656 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.490 ms/op
                 existUser·p0.50:   5.439 ms/op
                 existUser·p0.90:   7.004 ms/op
                 existUser·p0.95:   7.938 ms/op
                 existUser·p0.99:   10.060 ms/op
                 existUser·p0.999:  14.376 ms/op
                 existUser·p0.9999: 30.007 ms/op
                 existUser·p1.00:   31.490 ms/op

Iteration   2: 5.421 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.372 ms/op
                 existUser·p0.50:   5.186 ms/op
                 existUser·p0.90:   6.513 ms/op
                 existUser·p0.95:   7.315 ms/op
                 existUser·p0.99:   9.896 ms/op
                 existUser·p0.999:  25.406 ms/op
                 existUser·p0.9999: 28.358 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   3: 5.488 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.890 ms/op
                 existUser·p0.50:   5.341 ms/op
                 existUser·p0.90:   6.668 ms/op
                 existUser·p0.95:   7.324 ms/op
                 existUser·p0.99:   9.273 ms/op
                 existUser·p0.999:  24.928 ms/op
                 existUser·p0.9999: 30.191 ms/op
                 existUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 173790
  mean =      5.520 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 64243 
    [ 5.000,  7.500) = 100657 
    [ 7.500, 10.000) = 7415 
    [10.000, 12.500) = 963 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.890 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      6.734 ms/op
     p(95.0000) =      7.528 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     16.506 ms/op
     p(99.9900) =     29.860 ms/op
     p(99.9990) =     31.950 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.703 ±(99.9%) 0.247 ms/op
# Warmup Iteration   2: 6.781 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.896 ±(99.9%) 0.022 ms/op
Iteration   1: 5.490 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.724 ms/op
                 getUser·p0.50:   5.046 ms/op
                 getUser·p0.90:   6.947 ms/op
                 getUser·p0.95:   8.266 ms/op
                 getUser·p0.99:   11.485 ms/op
                 getUser·p0.999:  19.063 ms/op
                 getUser·p0.9999: 27.689 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   2: 5.633 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.605 ms/op
                 getUser·p0.50:   5.341 ms/op
                 getUser·p0.90:   6.816 ms/op
                 getUser·p0.95:   7.430 ms/op
                 getUser·p0.99:   11.207 ms/op
                 getUser·p0.999:  26.488 ms/op
                 getUser·p0.9999: 30.649 ms/op
                 getUser·p1.00:   31.359 ms/op

Iteration   3: 5.628 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.765 ms/op
                 getUser·p0.50:   5.259 ms/op
                 getUser·p0.90:   6.906 ms/op
                 getUser·p0.95:   7.700 ms/op
                 getUser·p0.99:   10.961 ms/op
                 getUser·p0.999:  28.718 ms/op
                 getUser·p0.9999: 30.943 ms/op
                 getUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171802
  mean =      5.583 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 65841 
    [ 5.000,  7.500) = 95739 
    [ 7.500, 10.000) = 7524 
    [10.000, 12.500) = 1771 
    [12.500, 15.000) = 473 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.605 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.873 ms/op
     p(95.0000) =      7.758 ms/op
     p(99.0000) =     11.190 ms/op
     p(99.9000) =     21.234 ms/op
     p(99.9900) =     30.665 ms/op
     p(99.9990) =     31.368 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.255 ±(99.9%) 0.375 ms/op
# Warmup Iteration   2: 8.641 ±(99.9%) 0.069 ms/op
# Warmup Iteration   3: 6.776 ±(99.9%) 0.030 ms/op
Iteration   1: 6.659 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.712 ms/op
                 listUser·p0.50:   6.341 ms/op
                 listUser·p0.90:   8.274 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   12.415 ms/op
                 listUser·p0.999:  28.311 ms/op
                 listUser·p0.9999: 32.879 ms/op
                 listUser·p1.00:   33.522 ms/op

Iteration   2: 6.793 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.449 ms/op
                 listUser·p0.50:   6.357 ms/op
                 listUser·p0.90:   8.405 ms/op
                 listUser·p0.95:   9.486 ms/op
                 listUser·p0.99:   12.861 ms/op
                 listUser·p0.999:  29.196 ms/op
                 listUser·p0.9999: 36.449 ms/op
                 listUser·p1.00:   37.224 ms/op

Iteration   3: 6.757 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.232 ms/op
                 listUser·p0.50:   6.349 ms/op
                 listUser·p0.90:   8.364 ms/op
                 listUser·p0.95:   9.781 ms/op
                 listUser·p0.99:   13.916 ms/op
                 listUser·p0.999:  25.385 ms/op
                 listUser·p0.9999: 31.130 ms/op
                 listUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 142418
  mean =      6.736 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 3624 
    [ 5.000,  7.500) = 112156 
    [ 7.500, 10.000) = 21392 
    [10.000, 12.500) = 3275 
    [12.500, 15.000) = 1242 
    [15.000, 17.500) = 319 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 104 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.712 ms/op
     p(50.0000) =      6.349 ms/op
     p(90.0000) =      8.348 ms/op
     p(95.0000) =      9.470 ms/op
     p(99.0000) =     13.058 ms/op
     p(99.9000) =     28.246 ms/op
     p(99.9900) =     34.194 ms/op
     p(99.9990) =     37.197 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.449 ± 1.876  ops/ms
ClientPb.existUser                       thrpt       3   5.979 ± 3.705  ops/ms
ClientPb.getUser                         thrpt       3   5.487 ± 1.886  ops/ms
ClientPb.listUser                        thrpt       3   4.815 ± 1.281  ops/ms
ClientPb.createUser                       avgt       3   5.693 ± 2.106   ms/op
ClientPb.existUser                        avgt       3   5.627 ± 1.612   ms/op
ClientPb.getUser                          avgt       3   5.643 ± 3.171   ms/op
ClientPb.listUser                         avgt       3   6.478 ± 0.346   ms/op
ClientPb.createUser                     sample  166722   5.756 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.236           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.356           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.454           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.534           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.805           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.345           ms/op
ClientPb.createUser:createUser·p1.00    sample          52.494           ms/op
ClientPb.existUser                      sample  173790   5.520 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.890           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.734           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.528           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.732           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.506           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.860           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.506           ms/op
ClientPb.getUser                        sample  171802   5.583 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.605           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.218           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.873           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.758           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.190           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.234           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.665           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.392           ms/op
ClientPb.listUser                       sample  142418   6.736 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.712           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.349           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.348           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.470           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.058           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.246           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.194           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.224           ms/op
