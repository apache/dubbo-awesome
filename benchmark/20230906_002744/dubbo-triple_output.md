# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.908 ops/ms
# Warmup Iteration   2: 5.283 ops/ms
# Warmup Iteration   3: 8.231 ops/ms
Iteration   1: 8.912 ops/ms
Iteration   2: 8.977 ops/ms
Iteration   3: 8.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.907 ±(99.9%) 1.314 ops/ms [Average]
  (min, avg, max) = (8.833, 8.907, 8.977), stdev = 0.072
  CI (99.9%): [7.593, 10.221] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.856 ops/ms
# Warmup Iteration   2: 8.062 ops/ms
# Warmup Iteration   3: 9.200 ops/ms
Iteration   1: 9.317 ops/ms
Iteration   2: 9.214 ops/ms
Iteration   3: 9.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.388 ±(99.9%) 3.997 ops/ms [Average]
  (min, avg, max) = (9.214, 9.388, 9.634), stdev = 0.219
  CI (99.9%): [5.392, 13.385] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.683 ops/ms
# Warmup Iteration   2: 7.489 ops/ms
# Warmup Iteration   3: 8.521 ops/ms
Iteration   1: 8.936 ops/ms
Iteration   2: 8.658 ops/ms
Iteration   3: 8.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.853 ±(99.9%) 3.087 ops/ms [Average]
  (min, avg, max) = (8.658, 8.853, 8.964), stdev = 0.169
  CI (99.9%): [5.766, 11.940] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.759 ops/ms
# Warmup Iteration   2: 7.201 ops/ms
# Warmup Iteration   3: 7.386 ops/ms
Iteration   1: 7.611 ops/ms
Iteration   2: 7.935 ops/ms
Iteration   3: 7.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.759 ±(99.9%) 2.996 ops/ms [Average]
  (min, avg, max) = (7.611, 7.759, 7.935), stdev = 0.164
  CI (99.9%): [4.763, 10.755] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 10.233 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.004 ms/op
Iteration   1: 3.671 ±(99.9%) 0.009 ms/op
Iteration   2: 3.615 ±(99.9%) 0.007 ms/op
Iteration   3: 3.470 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.586 ±(99.9%) 1.893 ms/op [Average]
  (min, avg, max) = (3.470, 3.586, 3.671), stdev = 0.104
  CI (99.9%): [1.693, 5.479] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.631 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.007 ms/op
Iteration   1: 3.472 ±(99.9%) 0.005 ms/op
Iteration   2: 3.416 ±(99.9%) 0.009 ms/op
Iteration   3: 3.599 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.496 ±(99.9%) 1.713 ms/op [Average]
  (min, avg, max) = (3.416, 3.496, 3.599), stdev = 0.094
  CI (99.9%): [1.783, 5.209] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.713 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.736 ±(99.9%) 0.007 ms/op
Iteration   1: 3.575 ±(99.9%) 0.005 ms/op
Iteration   2: 3.488 ±(99.9%) 0.006 ms/op
Iteration   3: 3.524 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.529 ±(99.9%) 0.795 ms/op [Average]
  (min, avg, max) = (3.488, 3.529, 3.575), stdev = 0.044
  CI (99.9%): [2.734, 4.323] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.408 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.764 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.307 ±(99.9%) 0.006 ms/op
Iteration   1: 4.311 ±(99.9%) 0.005 ms/op
Iteration   2: 4.196 ±(99.9%) 0.012 ms/op
Iteration   3: 4.135 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.214 ±(99.9%) 1.635 ms/op [Average]
  (min, avg, max) = (4.135, 4.214, 4.311), stdev = 0.090
  CI (99.9%): [2.579, 5.849] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.496 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.426 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.015 ms/op
Iteration   1: 3.572 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.996 ms/op
                 createUser·p0.999:  22.118 ms/op
                 createUser·p0.9999: 24.740 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   2: 3.606 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.526 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  22.020 ms/op
                 createUser·p0.9999: 28.508 ms/op
                 createUser·p1.00:   30.310 ms/op

Iteration   3: 3.664 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   7.818 ms/op
                 createUser·p0.999:  23.453 ms/op
                 createUser·p0.9999: 35.687 ms/op
                 createUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 265488
  mean =      3.614 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5064 
    [ 2.500,  5.000) = 249436 
    [ 5.000,  7.500) = 8757 
    [ 7.500, 10.000) = 1498 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     35.258 ms/op
     p(99.9990) =     36.004 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.694 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.010 ms/op
Iteration   1: 3.526 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.702 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  9.573 ms/op
                 existUser·p0.9999: 23.460 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   2: 3.542 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.466 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   5.059 ms/op
                 existUser·p0.99:   7.389 ms/op
                 existUser·p0.999:  20.249 ms/op
                 existUser·p0.9999: 23.492 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   3: 3.350 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   6.586 ms/op
                 existUser·p0.999:  23.020 ms/op
                 existUser·p0.9999: 34.436 ms/op
                 existUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 276607
  mean =      3.470 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10690 
    [ 2.500,  5.000) = 256577 
    [ 5.000,  7.500) = 7377 
    [ 7.500, 10.000) = 1422 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     16.184 ms/op
     p(99.9900) =     32.660 ms/op
     p(99.9990) =     35.077 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.655 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.013 ms/op
Iteration   1: 3.646 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.599 ms/op
                 getUser·p0.50:   3.568 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  23.164 ms/op
                 getUser·p0.9999: 26.106 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 3.783 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   7.734 ms/op
                 getUser·p0.999:  25.133 ms/op
                 getUser·p0.9999: 28.049 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   3: 3.678 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   7.331 ms/op
                 getUser·p0.999:  12.403 ms/op
                 getUser·p0.9999: 28.573 ms/op
                 getUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 259192
  mean =      3.701 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3590 
    [ 2.500,  5.000) = 242789 
    [ 5.000,  7.500) = 10315 
    [ 7.500, 10.000) = 1774 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 145 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     18.043 ms/op
     p(99.9900) =     28.052 ms/op
     p(99.9990) =     29.466 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.146 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.565 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.014 ms/op
Iteration   1: 4.300 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.917 ms/op
                 listUser·p0.50:   4.166 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  22.236 ms/op
                 listUser·p0.9999: 26.723 ms/op
                 listUser·p1.00:   27.623 ms/op

Iteration   2: 4.367 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.894 ms/op
                 listUser·p0.50:   4.178 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   9.781 ms/op
                 listUser·p0.999:  18.579 ms/op
                 listUser·p0.9999: 33.620 ms/op
                 listUser·p1.00:   33.817 ms/op

Iteration   3: 4.200 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.021 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  17.626 ms/op
                 listUser·p0.9999: 25.537 ms/op
                 listUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 223902
  mean =      4.288 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 205093 
    [ 5.000,  7.500) = 14272 
    [ 7.500, 10.000) = 2735 
    [10.000, 12.500) = 1080 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 233 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.894 ms/op
     p(50.0000) =      4.133 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.907 ± 1.314  ops/ms
ClientPb.existUser                       thrpt       3   9.388 ± 3.997  ops/ms
ClientPb.getUser                         thrpt       3   8.853 ± 3.087  ops/ms
ClientPb.listUser                        thrpt       3   7.759 ± 2.996  ops/ms
ClientPb.createUser                       avgt       3   3.586 ± 1.893   ms/op
ClientPb.existUser                        avgt       3   3.496 ± 1.713   ms/op
ClientPb.getUser                          avgt       3   3.529 ± 0.795   ms/op
ClientPb.listUser                         avgt       3   4.214 ± 1.635   ms/op
ClientPb.createUser                     sample  265488   3.614 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.110           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.482           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.119           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.184           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.258           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.307           ms/op
ClientPb.existUser                      sample  276607   3.470 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.149           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.985           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.481           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.184           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.660           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.127           ms/op
ClientPb.getUser                        sample  259192   3.701 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.057           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.584           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.438           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.043           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.052           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.557           ms/op
ClientPb.listUser                       sample  223902   4.288 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.894           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.133           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.306           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.809           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.554           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.817           ms/op
