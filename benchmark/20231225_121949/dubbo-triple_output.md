# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.649 ops/ms
# Warmup Iteration   2: 12.024 ops/ms
# Warmup Iteration   3: 12.366 ops/ms
Iteration   1: 12.528 ops/ms
Iteration   2: 12.634 ops/ms
Iteration   3: 12.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.604 ±(99.9%) 1.218 ops/ms [Average]
  (min, avg, max) = (12.528, 12.604, 12.651), stdev = 0.067
  CI (99.9%): [11.386, 13.822] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.091 ops/ms
# Warmup Iteration   2: 13.210 ops/ms
# Warmup Iteration   3: 13.258 ops/ms
Iteration   1: 13.124 ops/ms
Iteration   2: 13.091 ops/ms
Iteration   3: 13.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.130 ±(99.9%) 0.778 ops/ms [Average]
  (min, avg, max) = (13.091, 13.130, 13.176), stdev = 0.043
  CI (99.9%): [12.352, 13.908] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.746 ops/ms
# Warmup Iteration   2: 12.649 ops/ms
# Warmup Iteration   3: 12.938 ops/ms
Iteration   1: 12.918 ops/ms
Iteration   2: 12.874 ops/ms
Iteration   3: 12.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.882 ±(99.9%) 0.601 ops/ms [Average]
  (min, avg, max) = (12.853, 12.882, 12.918), stdev = 0.033
  CI (99.9%): [12.281, 13.482] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.661 ops/ms
# Warmup Iteration   2: 10.495 ops/ms
# Warmup Iteration   3: 10.631 ops/ms
Iteration   1: 10.773 ops/ms
Iteration   2: 10.583 ops/ms
Iteration   3: 10.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.662 ±(99.9%) 1.800 ops/ms [Average]
  (min, avg, max) = (10.583, 10.662, 10.773), stdev = 0.099
  CI (99.9%): [8.862, 12.462] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.054 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.004 ms/op
Iteration   1: 2.615 ±(99.9%) 0.005 ms/op
Iteration   2: 2.571 ±(99.9%) 0.003 ms/op
Iteration   3: 2.575 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.587 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (2.571, 2.587, 2.615), stdev = 0.024
  CI (99.9%): [2.140, 3.034] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.454 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.426 ±(99.9%) 0.004 ms/op
Iteration   1: 2.424 ±(99.9%) 0.004 ms/op
Iteration   2: 2.429 ±(99.9%) 0.004 ms/op
Iteration   3: 2.425 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (2.424, 2.426, 2.429), stdev = 0.003
  CI (99.9%): [2.370, 2.482] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.959 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
Iteration   2: 2.495 ±(99.9%) 0.003 ms/op
Iteration   3: 2.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (2.495, 2.500, 2.508), stdev = 0.007
  CI (99.9%): [2.379, 2.621] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.599 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.005 ms/op
Iteration   1: 2.984 ±(99.9%) 0.006 ms/op
Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
Iteration   3: 2.974 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.980 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.974, 2.980, 2.984), stdev = 0.005
  CI (99.9%): [2.881, 3.080] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.093 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.700 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.006 ms/op
Iteration   1: 2.554 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  11.744 ms/op
                 createUser·p0.9999: 14.016 ms/op
                 createUser·p1.00:   14.959 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  9.113 ms/op
                 createUser·p0.9999: 11.796 ms/op
                 createUser·p1.00:   12.435 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  8.684 ms/op
                 createUser·p0.9999: 11.147 ms/op
                 createUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379286
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 181436 
    [ 2.500,  3.750) = 193716 
    [ 3.750,  5.000) = 3308 
    [ 5.000,  6.250) = 306 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      8.772 ms/op
     p(99.9900) =     13.334 ms/op
     p(99.9990) =     14.338 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.725 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.576 ms/op
                 existUser·p0.999:  7.984 ms/op
                 existUser·p0.9999: 14.151 ms/op
                 existUser·p1.00:   15.860 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.736 ms/op
                 existUser·p0.999:  8.648 ms/op
                 existUser·p0.9999: 12.461 ms/op
                 existUser·p1.00:   13.189 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  8.552 ms/op
                 existUser·p0.9999: 11.649 ms/op
                 existUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384862
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 187333 
    [ 2.500,  3.750) = 194221 
    [ 3.750,  5.000) = 2532 
    [ 5.000,  6.250) = 286 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     13.926 ms/op
     p(99.9990) =     15.679 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.920 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  11.112 ms/op
                 getUser·p0.9999: 14.025 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.742 ms/op
                 getUser·p0.999:  6.785 ms/op
                 getUser·p0.9999: 13.109 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  8.088 ms/op
                 getUser·p0.9999: 12.732 ms/op
                 getUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385758
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 191998 
    [ 2.500,  3.750) = 189675 
    [ 3.750,  5.000) = 3282 
    [ 5.000,  6.250) = 331 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      7.691 ms/op
     p(99.9900) =     13.533 ms/op
     p(99.9990) =     14.273 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.483 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
Iteration   1: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.103 ms/op
                 listUser·p0.9999: 10.635 ms/op
                 listUser·p1.00:   11.469 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 11.055 ms/op
                 listUser·p1.00:   12.861 ms/op

Iteration   3: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.258 ms/op
                 listUser·p0.9999: 11.593 ms/op
                 listUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319768
  mean =      2.999 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 94373 
    [ 2.500,  3.750) = 187309 
    [ 3.750,  5.000) = 31211 
    [ 5.000,  6.250) = 5427 
    [ 6.250,  7.500) = 679 
    [ 7.500,  8.750) = 234 
    [ 8.750, 10.000) = 312 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.244 ms/op
     p(99.9900) =     11.174 ms/op
     p(99.9990) =     12.845 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.604 ± 1.218  ops/ms
ClientPb.existUser                       thrpt       3  13.130 ± 0.778  ops/ms
ClientPb.getUser                         thrpt       3  12.882 ± 0.601  ops/ms
ClientPb.listUser                        thrpt       3  10.662 ± 1.800  ops/ms
ClientPb.createUser                       avgt       3   2.587 ± 0.447   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.056   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.121   ms/op
ClientPb.listUser                         avgt       3   2.980 ± 0.100   ms/op
ClientPb.createUser                     sample  379286   2.529 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.689           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.772           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.334           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.959           ms/op
ClientPb.existUser                      sample  384862   2.492 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.947           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.564           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.552           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.926           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.860           ms/op
ClientPb.getUser                        sample  385758   2.486 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.670           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.691           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.533           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.729           ms/op
ClientPb.listUser                       sample  319768   2.999 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.827           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.244           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.174           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.484           ms/op
