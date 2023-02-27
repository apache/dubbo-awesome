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
# Warmup Iteration   1: 2.403 ops/ms
# Warmup Iteration   2: 5.728 ops/ms
# Warmup Iteration   3: 8.875 ops/ms
Iteration   1: 9.633 ops/ms
Iteration   2: 9.824 ops/ms
Iteration   3: 10.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.892 ±(99.9%) 5.458 ops/ms [Average]
  (min, avg, max) = (9.633, 9.892, 10.219), stdev = 0.299
  CI (99.9%): [4.434, 15.350] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.233 ops/ms
# Warmup Iteration   2: 9.267 ops/ms
# Warmup Iteration   3: 10.395 ops/ms
Iteration   1: 10.506 ops/ms
Iteration   2: 10.075 ops/ms
Iteration   3: 10.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.273 ±(99.9%) 3.972 ops/ms [Average]
  (min, avg, max) = (10.075, 10.273, 10.506), stdev = 0.218
  CI (99.9%): [6.302, 14.245] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.028 ops/ms
# Warmup Iteration   2: 8.630 ops/ms
# Warmup Iteration   3: 9.838 ops/ms
Iteration   1: 9.617 ops/ms
Iteration   2: 10.064 ops/ms
Iteration   3: 9.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.844 ±(99.9%) 4.075 ops/ms [Average]
  (min, avg, max) = (9.617, 9.844, 10.064), stdev = 0.223
  CI (99.9%): [5.769, 13.919] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.012 ops/ms
# Warmup Iteration   2: 7.882 ops/ms
# Warmup Iteration   3: 8.356 ops/ms
Iteration   1: 8.375 ops/ms
Iteration   2: 8.789 ops/ms
Iteration   3: 8.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.539 ±(99.9%) 4.014 ops/ms [Average]
  (min, avg, max) = (8.375, 8.539, 8.789), stdev = 0.220
  CI (99.9%): [4.525, 12.554] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.597 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.452 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.002 ms/op
Iteration   1: 3.206 ±(99.9%) 0.003 ms/op
Iteration   2: 3.091 ±(99.9%) 0.002 ms/op
Iteration   3: 3.144 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.147 ±(99.9%) 1.058 ms/op [Average]
  (min, avg, max) = (3.091, 3.147, 3.206), stdev = 0.058
  CI (99.9%): [2.089, 4.205] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.655 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.280 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.003 ms/op
Iteration   1: 3.086 ±(99.9%) 0.006 ms/op
Iteration   2: 3.093 ±(99.9%) 0.007 ms/op
Iteration   3: 3.159 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.113 ±(99.9%) 0.737 ms/op [Average]
  (min, avg, max) = (3.086, 3.113, 3.159), stdev = 0.040
  CI (99.9%): [2.376, 3.849] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.164 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.395 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.003 ms/op
Iteration   1: 3.169 ±(99.9%) 0.002 ms/op
Iteration   2: 3.142 ±(99.9%) 0.006 ms/op
Iteration   3: 3.075 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.129 ±(99.9%) 0.879 ms/op [Average]
  (min, avg, max) = (3.075, 3.129, 3.169), stdev = 0.048
  CI (99.9%): [2.250, 4.008] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.901 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.005 ms/op
Iteration   1: 3.684 ±(99.9%) 0.011 ms/op
Iteration   2: 3.706 ±(99.9%) 0.005 ms/op
Iteration   3: 3.670 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.687 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (3.670, 3.687, 3.706), stdev = 0.018
  CI (99.9%): [3.360, 4.014] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.424 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.010 ms/op
Iteration   1: 3.194 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   6.109 ms/op
                 createUser·p0.999:  12.014 ms/op
                 createUser·p0.9999: 22.596 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 3.107 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.285 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  20.382 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   3.535 ms/op
                 createUser·p0.99:   5.543 ms/op
                 createUser·p0.999:  12.714 ms/op
                 createUser·p0.9999: 19.562 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306129
  mean =      3.135 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21634 
    [ 2.500,  5.000) = 279120 
    [ 5.000,  7.500) = 4346 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     22.426 ms/op
     p(99.9990) =     23.423 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.547 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
Iteration   1: 3.070 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  9.508 ms/op
                 existUser·p0.9999: 17.765 ms/op
                 existUser·p1.00:   18.645 ms/op

Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  9.437 ms/op
                 existUser·p0.9999: 19.497 ms/op
                 existUser·p1.00:   20.709 ms/op

Iteration   3: 3.052 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  12.698 ms/op
                 existUser·p0.9999: 33.981 ms/op
                 existUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307937
  mean =      3.117 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22064 
    [ 2.500,  5.000) = 279989 
    [ 5.000,  7.500) = 4910 
    [ 7.500, 10.000) = 522 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     12.173 ms/op
     p(99.9900) =     32.775 ms/op
     p(99.9990) =     34.205 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.203 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.009 ms/op
Iteration   1: 3.222 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  18.799 ms/op
                 getUser·p0.9999: 24.087 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   2: 3.309 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.485 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  15.461 ms/op
                 getUser·p0.9999: 23.702 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   3: 3.258 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  15.262 ms/op
                 getUser·p0.9999: 20.540 ms/op
                 getUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294091
  mean =      3.263 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20350 
    [ 2.500,  5.000) = 266059 
    [ 5.000,  7.500) = 6841 
    [ 7.500, 10.000) = 381 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     16.734 ms/op
     p(99.9900) =     23.678 ms/op
     p(99.9990) =     24.406 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.931 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.755 ±(99.9%) 0.010 ms/op
Iteration   1: 3.767 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  14.843 ms/op
                 listUser·p0.9999: 20.005 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 3.798 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.501 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  14.536 ms/op
                 listUser·p0.9999: 18.992 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 3.735 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.321 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  12.867 ms/op
                 listUser·p0.9999: 14.565 ms/op
                 listUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254836
  mean =      3.767 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 247942 
    [ 5.000,  7.500) = 4788 
    [ 7.500, 10.000) = 1339 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 314 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     18.990 ms/op
     p(99.9990) =     21.019 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.892 ± 5.458  ops/ms
ClientPb.existUser                       thrpt       3  10.273 ± 3.972  ops/ms
ClientPb.getUser                         thrpt       3   9.844 ± 4.075  ops/ms
ClientPb.listUser                        thrpt       3   8.539 ± 4.014  ops/ms
ClientPb.createUser                       avgt       3   3.147 ± 1.058   ms/op
ClientPb.existUser                        avgt       3   3.113 ± 0.737   ms/op
ClientPb.getUser                          avgt       3   3.129 ± 0.879   ms/op
ClientPb.listUser                         avgt       3   3.687 ± 0.327   ms/op
ClientPb.createUser                     sample  306129   3.135 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.896           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.400           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.426           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.757           ms/op
ClientPb.existUser                      sample  307937   3.117 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.951           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.448           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.173           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.775           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.210           ms/op
ClientPb.getUser                        sample  294091   3.263 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.044           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.734           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.678           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.345           ms/op
ClientPb.listUser                       sample  254836   3.767 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.386           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.059           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.062           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.041           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.990           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.332           ms/op
